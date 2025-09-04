
# Use this repo

## Steps
1. Install Certbot
```
sudo snap install --classic certbot
sudo ln -s /snap/bin/certbot /usr/bin/certbot
```

2. Generate the certificate using nip.io domain format
```
sudo certbot certonly --standalone
```
3. Install Docker and Docker-Compose
4. Run the compose file
```
docker-compose up -d
```
5. Push and pull your images, enjoy it!

