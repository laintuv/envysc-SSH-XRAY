<h3 align="center">AUTOSCRIPT INSTALL SSH & V2RAYXRAY & SHADOWSOCKS & TROJAN x GRPC</h3>

<h3 align="center"> Supported Linux Distribution</h3>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04 LTS&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=20.04 LTS&color=red"></p>

<p align="center"><img src="https://img.shields.io/badge/Service-OpenSSH-success.svg">  <img src="https://img.shields.io/badge/Service-Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img   src="https://img.shields.io/badge/Service-Webmin-success.svg">  <img src="https://img.shields.io/badge/Service-Websocket-success.svg">   <img
src="https://img.shields.io/badge/Service-V2rayXray-success.svg">  <img src= "https://img.shields.io/badge/Service-shadowsocksGRPC-success.svg">  <img src="https://img.shields.io/badge/Service-TrojanGRPC-success.svg">  <img src="https://img.shields.io/badge/Service-VmessGRPC-success.svg"> <img src="https://img.shields.io/badge/Service-VlessGRPC-success.svg">

 <h3> Service & Port: </h3>
 
 ```
SSH Websocket	: 80 [OFF]
SSH SSL Websocket	: 443
Stunnel4		: 447, 777
Dropbear		: 109, 143
Badvpn		  : 7100-7900
Nginx		    : 81
Vmess TLS		: 443
Vmess None TLS	: 80
Vless TLS		: 443
Vless None TLS	: 80
Trojan GRPC		: 443
Trojan WS		: 443
Sodosok WS/GRPC         : 443
```

<h3>Install: </h3>

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/envy26/envysc/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```
