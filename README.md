# command

ssh-keygen -t ed25519 -C "gilab-laptop" -f "%USERPROFILE%\.ssh\my_custom_key"

mkdir -p ~/.ssh
chmod 700 ~/.ssh
echo "PASTE_COPIED_PUBLIC_KEY_HERE" >> ~/.ssh/authorized_keys
chmod 600 ~/.ssh/authorized_keys
