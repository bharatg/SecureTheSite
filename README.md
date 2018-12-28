# SecureTheSite
Hypertext Transfer Protocol Secure 

from Wikipedia
In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS), or, formerly,
its predecessor, Secure Sockets Layer (SSL)


### Procedure:
#### Ubuntu
 1. sudo add-apt-repository ppa:certbot/certbot
 2. sudo apt-get update
 3. sudo apt-get install python-certbot-nginx
 
 #### Ngnix
 sudo nano /etc/nginx/sites-available/default
 edit
     . . .
    server_name example.com www.example.com;
    . . .

sudo nginx -t
sudo systemctl reload nginx

Refer for more Details
https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04

 
 
