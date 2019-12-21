# Wireguard Install
## Installation
Download
```shell
$ wget -qO /usr/local/bin/wg-install https://git.io/JedO6
$ chmod +x /usr/local/bin/wg-install
```
If you have a FQDN configured you can skip this step, otherwise you have to open the script and change `ENDPOINT=$HOSTNAME` to `ENDPOINT="YOURIP`

Run installer
```shell
$ wg-install install
```

## Usage


```shell
$ wg-install add
```
