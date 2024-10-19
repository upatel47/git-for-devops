Terminal Command Reference
General Commands
clear: Clears the terminal screen.
pwd: Prints the current working directory.
ls: Lists files and directories in the current directory.
ls -l: Lists files and directories with detailed information.
whoami: Displays the current user's name.
Package Management (Debian/Ubuntu)
sudo apt install nginx: Installs Nginx web server.
sudo apt install jenkins: Installs Jenkins.
sudo groupadd devops: Creates a new group named devops.
File and Directory Management
cd /var/www/html: Changes directory to /var/www/html.
vim index.nginx-debian.html: Opens the specified file in Vim for editing.
sudo vim index.nginx-debian.html: Opens the file with superuser privileges.
cat index.nginx-debian.html: Displays the contents of the file.
mkdir xyz: Creates a new directory named xyz.
touch demo.txt: Creates an empty file named demo.txt.
User Management
useradd kaleen: Creates a new user named kaleen.
sudo useradd -m kaleen: Creates a new user with a home directory.
sudo passwd kaleen-baiya: Sets the password for user kaleen-baiya.
sudo passwd user4: Sets the password for user4.
Service Management
service httpd restart: Restarts the Apache HTTP server.
sudo systemctl restart httpd: Restarts the Apache HTTP server with superuser privileges.
systemctl httpd status: (Incorrect) Should be systemctl status httpd.
Searching and Filtering
grep warning Zookeeper_2k.log: Searches for the word "warning" in the specified log file.
cat /etc/passwd | grep muna: Searches for muna in the password file.
awk '/WARN/ {print $1}' Zookeeper_2k.log.1: Searches for lines containing "WARN" and prints the first field.
find . -name *.log: Searches for all .log files in the current directory.
Git Commands
git init: Initializes a new Git repository.
git add .: Stages all changes in the current directory for commit.
git commit -m "message": Commits staged changes with a specified message.
git status: Displays the status of the working directory and staging area.
git log: Shows the commit history.
