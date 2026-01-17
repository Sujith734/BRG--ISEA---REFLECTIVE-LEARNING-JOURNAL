## Lab 3 – Apache Web Server Setup

## Purpose
To install, configure, and manage the Apache2 web server on Ubuntu.

## What Was Done
- Updated package lists using `sudo apt update` and installed Apache with `sudo apt install apache2`.
- Opened the default Apache page using `127.0.0.1` in a browser.
- Found the system IP address using `ip a` and accessed a partner’s Apache webpage.
- Edited the default web page with:
  `sudo nano /var/www/html/index.html`
- Used `nmap` to scan open ports before and after removing Apache.
- Enabled the UFW firewall and allowed traffic on port 80 (HTTP).
- Tested SSH connections with a partner.
- Created a new user and compared entries in the `/etc/passwd` file.

## Key Learning

This lab demonstrated how Linux services operate, how firewalls control network access, and how Apache delivers web content across a network.

## Screenshots
<img width="767" height="455" alt="image" src="https://github.com/user-attachments/assets/b084f809-f5de-4cbc-a649-2d472de73a94" />

<img width="871" height="371" alt="image" src="https://github.com/user-attachments/assets/e53cc839-4652-4fca-b415-3c093d32eb8f" />

<img width="835" height="472" alt="image" src="https://github.com/user-attachments/assets/ab1b156d-dbdf-4734-b3e0-c72df5cf892c" />

