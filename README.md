# Main
echo "# Main" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mendor77/Main.git
git push -u origin main
Generate a key if you don’t already have one:
ssh-keygen -t ed25519 -C "your_email@example.com"
Add your SSH key to GitHub:
Copy the contents of ~/.ssh/id_ed25519.pub →
Go to https://github.com/settings/keys
 → New SSH key → Paste it.
Update your remote to SSH:
git remote set-url origin git@github.com:mendor77/Main.git
