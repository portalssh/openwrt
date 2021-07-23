# List Config DNS-over-HTTPS

* DNS-over-HTTPS google-standart (global DNS resolution service that you can use as an alternative to your current DNS provider)
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/google.conf"
```
* DNS-over-HTTPS cloudfare-standart (fast DNS service which functions as a recursive name server providing domain name resolution for any host on the Internet)
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/cloudfare.conf"
```
* Config DNS-over-HTTPS opendns for openwrt
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/opendns.conf"
```
* Config DNS-over-HTTPS adguard for openwrt
```
wget -O /etc/config/https-dns-proxy "https://raw.githubusercontent.com/portalssh/openwrt/main/dns/adguard.conf"
```
