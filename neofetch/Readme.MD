* Install Neofetch Openwrt
```
opkg install libustream-openssl ca-bundle ca-certificates wget bash nano
wget -O /bin/neofetch "https://raw.githubusercontent.com/portalssh/openwrt/main/neofetch/neofetch"
chmod +x /bin/neofetch
sed -i 's/\[ -f \/etc\/banner \] && cat \/etc\/banner/#&/' /etc/profile
sed -i 's/\[ -n "$FAILSAFE" \] && cat \/etc\/banner.failsafe/& || \/bin\/neofetch/' /etc/profile
```

* Modif Banner Standar Openwrt
```
wget -O /etc/banner "https://raw.githubusercontent.com/portalssh/openwrt/main/neofetch/banner"
```
