# SecureTheSite
Hypertext Transfer Protocol Secure 

from Wikipedia
In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS), or, formerly,
its predecessor, Secure Sockets Layer (SSL)

![https](https://strongarm.io/wp-content/uploads/2017/11/HTTPS_icon.png)

### Procedure:
#### Ubuntu
```
sudo apt-get upgrade
sudo apt-get update
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:certbot/certbot
sudo apt-get update
sudo apt-get install python-certbot-nginx
 ```
 
 #### Ngnix
 ```
 sudo nano /etc/nginx/sites-available/default

 edit
    > . . .
    > server_name example.com www.example.com;
    > . . .
```



```
sudo nginx -t
sudo systemctl reload nginx
```


```
sudo certbot --nginx -d example.com -d www.example.com
```

Refer for more Details
https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04

 
 
