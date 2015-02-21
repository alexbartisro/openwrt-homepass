# openwrt-homepass
HomePass for OpenWRT. Forked from https://gist.github.com/masterdje/7031189

Now allows to specify a SSID for each MAC.

Place the list in /etc/homepass.list and the script in /usr/bin/homepass.sh. Set the script as executable.
Then call the script from cron every few minutes using the provided crontab template.

To activate cron in OpenWRT: log in and run "/etc/init.d/cron enable".
