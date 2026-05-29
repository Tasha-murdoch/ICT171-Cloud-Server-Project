This script automates several common server administration tasks for my project.

The script was created to reduce the amount of manual maintenance required on the Ubuntu server which is hosting the WordPress website.

Features

The script performs the following actions:

Updates Ubuntu packages
Checks Apache server status
Displays disk usage information
Displays memory usage information



To make the script work your first must make the script executable:


chmod +x server-maintenance.sh


The you can run the script:

./server-maintenance.sh
Output


The this then produces:

Terminal output showing system information
Timestamped backup files
MySQL database export files
Future Improvements


Future improvements of this script may include:

Automatic cloud backup uploads
Email notifications
Scheduled cron execution
Log rotation support
