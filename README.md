# How to setup OpenVPN server on UBUNTU

|Command|Description|
|-----|--------|
|ip a show eth0|check local ip|
|dig +short myip.opendns.com @resolver1.opendns.com|check external ip|
|git clone https://github.com/DrShams/vpn_server.git |clone this repo|
|chmod +x openvpn_install.sh|add execution permission to the file|
|sudo ./openvpn_install.sh|execute .sh script - then answer to the questions|
|sudo systemctl status openvpn-server@server.service|check status of the service|
|netstat --tcp --udp --listening --program --numeric | grep -i openvpn|make sure port 1194 is open, if not the port|

##At the end .ovpn file will be located in /root directory
Welcome to free internet!
