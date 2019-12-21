# Wireguard Install
## Requirements
Currently the script is only tested on Debian 10 additionally you need a configured FQDN and the server has to be reachable via this FQDN.

## Installation
Download
```shell
wget -qO /usr/local/bin/wg-install https://git.io/JedO6
chmod +x /usr/local/bin/wg-install
```
Run installer
```shell
wg-install install
```

## Usage

Add a new client
```shell
wg-install add
```
Delete a client
```shell
wg-install delete
```
