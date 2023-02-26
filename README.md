# proxyout
list of open free proxy, updated bi-hourly (as long as my localhost alive) ^_^
for the time being, only https proxy.


## Direct link to output files
- [https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.json](https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.json)
- [https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.txt](https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.txt)


## Test method:
- check the port is opened\
/usr/bin/nmap -P0 $aip -p $aport

- check ip\
/usr/bin/curl --max-time 15 -k -s -x '$aip:$aport' https://api.ipify.org/

## Thanks to:
- https://api.ipify.org/
- https://ifconfig.me/ip
- https://api.my-ip.io/ip


Last updated at Sun, 26 Feb 2023 22:35:58 +0700 -- found 256 proxy