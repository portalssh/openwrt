# List Config DNS-over-HTTPS

* DNS-over-HTTPS google-standart (global DNS resolution service that you can use as an alternative to your current DNS provider)
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/google.conf"
```
* DNS-over-HTTPS cloudfare-standart (fast DNS service which functions as a recursive name server providing domain name resolution for any host on the Internet)
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/cloudfare-standart.conf"
```
* DNS-over-HTTPS opendns-standart (DNS servers with custom filtering that protects your device from malware)
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/opendns-standart.conf"
```
* DNS-over-HTTPS adguard-standart (These servers provide blocking ads, tracking and phishing)
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/adguard-default.conf"
```
