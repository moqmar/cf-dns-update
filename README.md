# Cloudflare DNS Updater

Shell script that will update a Cloudflare record to the public IP of the server the script is running on every 5 minutes (only of the IP has changed), using a systemd timer.

Installation: `git clone https://github.com/moqmar/cf-dns-update.git /tmp/cf-dns-update && cd /tmp/cf-dns-update && source install`
