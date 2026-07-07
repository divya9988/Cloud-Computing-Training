Day 5 - Task 5 (Web Server Deployment)  
      - Task 6 (Bash Automation Script)
      - Date: 06/07/2026

## Task: Apache Web Server Deployment

## Completed the following activities:

Installed the Apache web server on Ubuntu.

Started and enabled the Apache service.

Created a custom webpage using HTML.

Added project title, name, roll number, branch, and date & time.

Accessed the webpage using the server IP address from a browser.

Verified successful deployment of the website.


## Commands practiced:

sudo apt install apache2

sudo systemctl start apache2

sudo systemctl enable apache2

sudo systemctl status apache2

sudo nano /var/www/html/index.html

hostname -I (http://localhost) or ID used to test it

Outcome: Successfully deployed and accessed a custom webpage through the Apache web server.


# Task: Bash Automation Script

## Completed the following activities:

Created a Bash script named server_health.sh that displays:

Current date and time

Logged-in user

Hostname

IP address

Disk usage

## Commands used inside the script:

date

whoami

hostname

hostname -I

df -h

free -h

uptime

Memory usage

CPU load

System uptime

Outcome: Successfully developed an automation script that provides a formatted health report of the Linux server
      

