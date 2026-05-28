
Apache2 was installed using the following command:


apt install apache2 -y


The Apache service status was verified using:


systemctl status apache2
<img width="1301" height="461" alt="image" src="https://github.com/user-attachments/assets/13240155-f774-4de9-ba40-ea61ad96a6b0" />

The service was confirmed to be active and running.


apt update && apt upgrade -y
apt install apache2 -y

## Verification
- Apache service running
- Default page visible at server IP
