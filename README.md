# How to setup OpenVPN server on UBUNTU
VPN server on Ubuntu

```
ip a show eth0
dig +short myip.opendns.com @resolver1.opendns.com
git clone https://github.com/DrShams/vpn_server.git
chmod +x openvpn_install.sh
sudo ./openvpn_install.sh
sudo systemctl status openvpn-server@server.service
netstat --tcp --udp --listening --program --numeric | grep -i openvpn
```

Welcome to free internet!
