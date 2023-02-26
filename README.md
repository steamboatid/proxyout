# proxyout
list of open free proxy

## Direct link to output files
- [https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.json](https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.json)
- [https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.txt](https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy.txt)


## Test method:
- check the port is opened\
/usr/bin/nmap -P0 $aip -p $aport

- check ip\
/usr/bin/curl --max-time 15 -k -s -x '$aip:$aport' https://api.ipify.org/

## Thanks to:
- [https://api.ipify.org/](https://api.ipify.org/)
