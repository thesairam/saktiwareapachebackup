# Apache Backup for saktiware.com

This directory contains backups of the Apache configuration files and SSL certificates for the domains `nas.saktiware.com` and `www.saktiware.com`.

## Directory Structure


## File Descriptions

- **fullchain.pem**: Contains the complete SSL certificate chain for the respective domain, including the server and intermediate certificates.

- **privkey.pem**: The private key associated with the SSL certificate for the respective domain. This file must be kept secure.

- **nextcloud.conf**: The Apache configuration file located in the `sites-available` directory for the Nextcloud application on **nas.saktiware.com**.

- **nextcloud-enabled.conf**: The corresponding configuration file in the `sites-enabled` directory indicating that the site is enabled in Apache.

- **www.saktiware.com.conf**: The Apache configuration file in the `sites-available` directory for the **www.saktiware.com** domain.

- **www-enabled.conf**: The configuration file in the `sites-enabled` directory for **www.saktiware.com** indicating that the site is enabled.

## Usage

This backup serves as a safety net for your Apache configurations and SSL certificates. In the event of configuration issues or SSL certificate expirations, you can restore the relevant files from this backup.

**Important**: Regularly back up these files and ensure they are stored securely to prevent unauthorized access to your SSL private keys.

