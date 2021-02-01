# Wireguard Install
A lightweight script to simplify the setup of Wireguard and the process of adding new clients.   
Furthermore a QR code for the setup of mobile devices is generated.

## Requirements
Make sure you have the latest Debian version installed, otherwise the installation will fail
```shell
apt update && apt upgrade -y && reboot
```


## Installation
Download
```shell
wget -qO /usr/local/bin/wgm https://git.io/JtRFm
chmod +x /usr/local/bin/wgm
```
Run installer
```shell
wgm
```

## Usage
```shell
wgm
```
