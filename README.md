# Kovic
Kovic.com is an e-commerce website where users can purchase from their favorite toy and plushy brands all on one website. The main purpose of this project is to showcase our ability to create a web architecture.

## Tools
This web architecture was created by using an LNMP web stack. It was made using Linux, Nginx, MySQL, PHP, AWS EC2, and ufw firewall. SSL was used for encryption. 

## File Placement
- kovic-server1.com, kovic-server2.com, kovic-server3.com, and reverse will all go in ```/etc/nginx/sites-available/```
- a symbolic link for each server must be made in ```/etc/nginx/sites-enabled/``` pointing to ```/etc/nginx/sites-available/```
- kovic1.com, kovic2.com, and kovic3.com directories go in ```/var/www/```
- kovic.key goes in ```/etc/ssl/private/```
- kovic.crt goes in ```/etc/ssl/certs/```

After all files are in their correct directories, run ```sudo systemctl restart nginx```

## Video
You may see a demonstration of this website from me and my partner with this link: https://www.youtube.com/watch?v=5c2gu-pZFhg
