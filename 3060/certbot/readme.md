# Certbot 

Install certbot and the cloudflare plugin

```
apt install certbot python3-certbot-dns-cloudflare
```

Copy the contents of cli.ini to /etc/letsencrypt/cli.ini
Copy the contents of cloudflare.ini to /etc/cloudflare.ini and replace TOKEN with teh proper account token. (1password maybe?)

```
chmod 400 /etc/cloudflare.ini
```

