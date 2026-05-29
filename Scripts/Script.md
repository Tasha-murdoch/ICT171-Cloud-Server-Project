Server Maintenance Script
Purpose

This script automates several common server administration tasks for the ICT171 cloud server project.

The script was created to reduce the amount of manual maintenance required on the Ubuntu server hosting the WordPress website.

Features

The script performs the following actions:

Updates Ubuntu packages
Checks Apache server status
Displays disk usage information
Displays memory usage information
Creates a compressed backup of the WordPress files
Creates a MySQL database backup
How to Run

Make the script executable:

chmod +x server-maintenance.sh

Run the script:

./server-maintenance.sh
Output

The script produces:

Terminal output showing system information
Timestamped backup files
MySQL database export files
Future Improvements

Future improvements may include:

Automatic cloud backup uploads
Email notifications
Scheduled cron execution
Log rotation support
