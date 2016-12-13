# openwrt-homepass
# HomePass for OpenWRT. Forked from https://github.com/Nephiel/openwrt-homepass
# Updated in Dec. 2016 by trusk89 https://github.com/trusk89/openwrt-homepass

Now allows to specify a SSID for each MAC.

Place the list in /etc/homepass.list and the script in /usr/bin/homepass.sh. Set the script as executable.
Then call the script from cron every few minutes using the provided crontab template.

To activate cron in OpenWRT: log in and run "/etc/init.d/cron enable".

Feel free to open PRs with more MACs.

I have tested it with OpenWRT 15.05 on a Dlink Dir-600 B2 and it works perfectly. If needed or requested, 
I will probably do a video tutorial on setting it up.
