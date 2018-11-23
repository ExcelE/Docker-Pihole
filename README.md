# Docker-Pihole

This repo will help you setup your Pihole in a Docker Container in just a few minutes.

### Pre-requisites:  
1) Docker  
2) Docker-Compose  
3) Linux OS  

### Steps:  
1) Clone repo  
2) ```cd Docker-Pihole```  
3) ```sudo docker-compose up -d```  
4) Go to your admin page by typing ```http://IP-ADDRESS/admin``` where IP-ADDRESS is your host machine's address.  

*Tip: to change your web admin password, edit the ```docker-compose.yml```'s ```- WEBPASSWORD=admin``` to anything you want.  

## Credits:  
1) https://visibilityspots.org/dockerized-cloudflared-pi-hole.html  