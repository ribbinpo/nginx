# Nginx
This is configured nginx reverse proxy with SSL (HTTPs)

1. add `certificate.crt` and `private.key` to `certs/` directory
2. update `default.conf` file
   - DNS_NAME: domain name of the server doesn't need protocol e.g. `example.com`
   - PRIVATE_IP: IP of service in the server e.g. `127.0.0.1`
   - PORT: port of service in the server e.g. `4000`
3. running `docker compose up -d`
