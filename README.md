# Wordpress docker-compose stack with SSL and redis
![WP](GitHub-Mark2.png)

⚠️⚠️⚠️ STACK IS NOT YET READY FOR PRODUCTION USE, USE IT WITH CAUTION ⚠️⚠️⚠️
## References
https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose\
https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-20-04
## Prerequisites:
### Docker
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04
### Docker-compose
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04

## Usage

Clone repository: \
`git clone https://github.com/DjordjeVucinac82/444noresponse.git` \
`cd 444noresponse/`

Rename .env.example to .env: \
`mv .env.example .env` \
Populate paswords fields in new .env file (your_password)

Open ports to www: 22, 80, 443, 8080

Start docker-compose: \
`sudo chmod +x init-letsencrypt.sh` \
`sudo ./init-letsencrypt.sh`

### DNS and Domain name

TODO - I'll make new repository for new environment. Domain name should be A records domain name to IP.