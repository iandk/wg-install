# Wireguard Install
## Installation
Download
```
wget -qO /usr/local/bin/wg-install https://git.io/JedO6
chmod +x /usr/local/bin/wg-install
```
If you have a FQDN configured you can skip this step, otherwise you have to open the script and change `ENDPOINT=$HOSTNAME` to `ENDPOINT="YOURIP`

Run installer
```
wg-install install
```

## Usage


```
wg-install add
```
