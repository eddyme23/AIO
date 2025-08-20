 <p align="center">

<h2 align="center">
This auto installer script is free of charge.
</h2>

<h2 align="center">
Auto Script Install XRAY/SSH Websocket Service
<img src="https://img.shields.io/badge/Release-v3.0-red.svg"></h2>

</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center">
 <img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"width="200"></p>
 
<p align="center">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2011&message=Bullseye&color=purple">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2012&message=Bookworm&color=purple">
</p>

<p align="center">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
 <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2022&message=Lts&color=red">
</p>

<h2 align="center">Network VPN</h2>
<p align="center">
 <img src="https://img.shields.io/badge/Service-SSH_Over_Websocket-success.svg">
 <img src="https://img.shields.io/badge/Service-SSH_UDP_Custom-success.svg">
 <img src="https://img.shields.io/badge/Service-SSH_Dropbear-success.svg">
 <img src="https://img.shields.io/badge/Service-Stunnel4-success.svg">
 <img src="https://img.shields.io/badge/Service-Fail2Ban-brightgreen">
 <img src="https://img.shields.io/badge/Service-OpenVPN-brightgreen">
<p align="center">
 <img src="https://img.shields.io/badge/Service-XRAY_VLESS-success.svg"> 
 <img src="https://img.shields.io/badge/Service-XRAY_VMESS-success.svg"> 
 <img src="https://img.shields.io/badge/Service-XRAY_TROJAN-success.svg">
 <img src= "https://img.shields.io/badge/Service-Websocket-success.svg">
 <img src= "https://img.shields.io/badge/Service-GRPC-success.svg">
 <img src= "https://img.shields.io/badge/Service-Shadowsocks-success.svg">  
<p <p align="center"><img src="https://img.shields.io/badge/Service-Webmin-success.svg">
 <img src="https://img.shields.io/badge/Service-Helium-success.svg">
<p <p align="center"><img src="https://wangchujiang.com/sb/status/stable.svg">



PLEASE MAKE SURE YOUR DOMAIN SETTINGS IN YOUR CLOUDFLARE AS BELOW (SSL/TLS SETTINGS)<br>
<br>

1. Your SSL/TLS encryption mode is Full
2. Enable SSL/TLS Recommender ✅
3. Edge Certificates > Disable Always Use HTTPS (off)

<br>
♦️ For Debian 10 / 11 / 12 For First Time Installation (Update Repo) <br>
 
  ```html
 apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
  ```
  ♦️ For Ubuntu 18.04 / 20.04 / 22.04 For First Time Installation (Update Repo) <br>
  
  ```html
 apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
 ```
♦️ Installation Link <br>

  ```html
apt --fix-missing update && apt update && apt upgrade -y && apt install -y bzip2 gzip coreutils screen dpkg wget vim curl nano zip unzip && wget -q https://raw.githubusercontent.com/eddyme23/AIO/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
  ```
<b>

[ SERVICES ] <br>
<br>
✅ SSH WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY VMESS WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY VLESS WEBSOCKET TLS & NON-TLS 443/80<br>
✅ XRAY TROJAN WEBSOCKET TLS & NON-TLS 443/80<br>
✅ STUNNEL TLS 443<br>
✅ SLOWDNS 53<br>
✅ UDP HYSTERIA<br>
<br>

[ OTHER SERVICES ] <br>
<br>
✅ NEW UPDATE BBRPLUS 5.15.96 <br>
✅ BANDWITH MONITOR <br>
✅ RAM MONITOR <br>
✅ DNS CHANGER <br>
✅ NETFLIX REGION CHECKER <br>
✅ CHECK LOGIN USER <br>
✅ CHECK CREATED CONFIG <br>
✅ AUTOMATIC CLEAR LOG <br>
✅ AUTOMATIC VPS REBOOT <br>
✅ BACKUP & RESTORE <br>
✅ XRAYCORE CHANGER <br>
✅ VIRTUAL SWAPRAM <br></br>




Original Script by https://github.com/NevermoreSSH/Blueblue