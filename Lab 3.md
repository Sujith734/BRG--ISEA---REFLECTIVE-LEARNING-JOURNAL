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
<img width="648" height="197" alt="image" src="https://github.com/user-attachments/assets/45ff1abf-0e7b-40fa-b67c-3c6b6f8d69c0" />


<img width="871" height="371" alt="image" src="https://github.com/user-attachments/assets/e53cc839-4652-4fca-b415-3c093d32eb8f" />

<img width="835" height="472" alt="image" src="https://github.com/user-attachments/assets/ab1b156d-dbdf-4734-b3e0-c72df5cf892c" />

<img width="896" height="631" alt="image" src="https://github.com/user-attachments/assets/65ab1cd9-fee8-4f90-9de7-a01e1ac9abf2" />

<img width="592" height="478" alt="image" src="https://github.com/user-attachments/assets/10119f90-8b9b-46de-bf65-829b7880be90" />

<img width="703" height="497" alt="image" src="https://github.com/user-attachments/assets/ceb796bc-8abf-439d-9f0d-2dfdfc54bb9d" />

<img width="700" height="382" alt="image" src="https://github.com/user-attachments/assets/a311e4b7-0fb2-43df-84dd-1dc5f0c2d618" />

<img width="656" height="487" alt="image" src="https://github.com/user-attachments/assets/a4b3e460-bc11-4fd5-86a7-468d036dc600" />





