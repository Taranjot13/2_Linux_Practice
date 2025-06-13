
# SSH & Remote Access

🔹 SSH Key
ssh-keygen -t ed25519 -C "your_email"

cat ~/.ssh/id_ed25519.pub

🔹 Connect to Server
ssh user@host

🔹 Copy Files
scp file user@host:/path

rsync -av file user@host:/path
