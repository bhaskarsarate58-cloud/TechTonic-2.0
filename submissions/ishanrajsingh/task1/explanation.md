mkdir cyber_lab - # Create directory cyber_lab
cd cyber_lab - # Select directory cyber_lab

touch visible.txt - # Create visible.txt

touch .secret.txt - # Create hidden file .secret.txt

chmod 444 visible.txt - # Change permissions of visible.txt to read-only (for everyone)

ls -la - # List all files including hidden

ls -la > listing.txt - # Redirect ls -la output into a file (e.g., listing.txt)
