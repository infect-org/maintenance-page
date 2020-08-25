# Install the Caddy system service

1. `sudo nano /etc/systemd/system/caddy.service`
2. paste the content of `caddy.service` into the file, change paths as required, save it
3. reload services `sudo systemctl daemon-reload`
4. enable the service `sudo systemctl enable caddy`
5. start the server `sudo systemctl start caddy`
6. check if caddy is running `sudo journalctl -fn 699 -u caddy`