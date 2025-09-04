
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
4. Copy the certificates in a new directory called certs
3. Install Docker and Docker-Compose (This reference to the certs directory)
4. Run the compose file
```
docker-compose up -d
```
5. Push and pull your images, enjoy it!

