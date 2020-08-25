# INFECT Maintenance Page

1. Install Caddy Server https://caddyserver.com/
2. create the ubuntu user `useradd -m ubuntu` if not exists
2. Clone this repository into `/home/ubuntu/apps/maintenance-page`
3. Install the system service using the instructions in the `sys` folder

The server will automatically request SSL certificates if the a records for the served domains point a http request on port to this server.
