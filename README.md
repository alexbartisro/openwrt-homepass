# Notice: a open network with just MAC filtering is an insecurity. Use at your own risk.

## openwrt-homepass
## HomePass for OpenWRT. Forked from https://github.com/Nephiel/openwrt-homepass
## Updated in Dec. 2016 by trusk89 https://github.com/trusk89/openwrt-homepass

Now allows to specify a SSID for each MAC.

Place the list in /etc/homepass.list and the script in /usr/bin/homepass.sh. Set the script as executable.
Then call the script from cron every few minutes using the provided crontab template.

To activate cron in OpenWRT: log in and run "/etc/init.d/cron enable".

Feel free to open PRs with more MACs.

I have tested it with OpenWRT 15.05 on a Dlink Dir-600 B2 and it works perfectly. If needed or requested, 
I will probably do a video tutorial on setting it up.

## Tutorial
[![LONG TUTORIAL](https://img.youtube.com/vi/64_B2qzNH4o/0.jpg)](https://www.youtube.com/watch?v=64_B2qzNH4o)

<span class="badge-paypal"><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=F5UAFVHBPQWXQ" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-bitcoin"><a href="http://i.imgur.com/wGR65b3.png" title="Donate once-off to this project using Bitcoin"><img src="https://img.shields.io/badge/bitcoin-donate-yellow.svg" alt="Bitcoin donate button" /></a></span>
