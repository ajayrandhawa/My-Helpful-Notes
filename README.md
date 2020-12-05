# My-Helpful-Notes

# AWS EC2

### PERMISSION ERROR FILE UPLOADING FILEZILLA
chmod 757 -R /var/www/html

### FOLDER PERMESSION RESET TO EXECUTE
sudo chown -R ec2-user:ec2-user /var/www/html
sudo chmod -R 755 /var/www/html

### RESTART FTP
sudo systemctl restart vsftpd
