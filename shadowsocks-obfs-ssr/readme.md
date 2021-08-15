* Config Shadowsocks-OBFS-SSR Openwrt
```
wget -O /etc/config/shadowsocks "https://raw.githubusercontent.com/portalssh/openwrt/main/shadowsocks-obfs-ssr/shadowsocks"
wget -O /etc/config/shadowsocksr "https://raw.githubusercontent.com/portalssh/openwrt/main/shadowsocks-obfs-ssr/shadowsocksr"
```

* Downgrade luci-app-shadowsocksr "fix error log luci-app-shadowsocksr"
```
opkg remove luci-app-shadowsocksr
cd /tmp
wget https://github.com/portalssh/openwrt/raw/main/shadowsocks-obfs-ssr/luci-app-shadowsocksr_1.8.1-2_all.ipk && opkg install *ipk
wget -O /usr/lib/lua/luci/controller/shadowsocksr.lua "https://raw.githubusercontent.com/portalssh/openwrt/main/shadowsocks-obfs-ssr/config/shadowsocksr.lua"
```
* Added Status openvpn with comand CLI "openvpn-status"
```
wget -O /usr/bin/openvpn-status "https://raw.githubusercontent.com/portalssh/openwrt/main/shadowsocks-obfs-ssr/openvpn-status" && chmod +x /usr/bin/openvpn-status
```
