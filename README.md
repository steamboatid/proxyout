# proxyout
list of open free socks5 proxy, updated bi-hourly (as long as my localhost alive) ^_^
for the time being, only socks5 proxy.


## Direct link to output files
- https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy-socks5.json
- https://raw.githubusercontent.com/steamboatid/proxyout/main/proxy-socks5.txt


## Test method:
- check the port is opened\
/usr/bin/nmap -P0 $aip -p $aport

- check ip\
/usr/bin/curl --max-time 15 -k -s -x '$aip:$aport' https://api.ipify.org/

- check with alive website\
/usr/bin/links2 -http-bugs.no-compression 1 -retries 2 -receive-timeout 10
-socks-proxy $prxe -source 'https://$adom/'  2>&1 | grep -o '$patt' | wc -l


## Thanks to:
- https://proxylist.geonode.com/api/proxy-list?limit=500&page=1&sort_by=lastChecked&sort_type=desc&protocols=socks5
- https://proxylist.geonode.com/api/proxy-list?limit=500&page=1&sort_by=lastChecked&sort_type=desc&protocols=socks4
- http://pubproxy.com/api/proxy?format=json&level=anonymous&type=socks5&last_check=60&speed=15
- https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/socks5.txt
- https://raw.githubusercontent.com/rdavydov/proxy-list/main/proxies_anonymous/socks5.txt
- https://raw.githubusercontent.com/prxchk/proxy-list/main/socks5.txt
- https://raw.githubusercontent.com/HyperBeats/proxy-list/main/socks5.txt
- https://raw.githubusercontent.com/jetkai/proxy-list/main/online-proxies/txt/proxies-socks5.txt
- https://proxypremium.top/socks-proxy-list
- https://www.proxydocker.com/en/socks5-list/
- https://scrapingant.com/free-proxies/
- https://proxyhub.me/en/om-sock5-proxy-list.html
- https://www.freeproxy.world/?type=socks5&anonymity=&country=&speed=&port=&page=1

## Thanks to ip checker:
https://api.my-ip.io/ip
https://api.ipify.org/
https://ifconfig.me/ip
https://api.ip.sb/ip
https://ipecho.net/plain
http://checkip.dyndns.org/
http://myexternalip.com/raw
http://checkip.amazonaws.com/


Last updated at Sat, 18 Mar 2023 08:06:28 +0700 -- found 0 socks5 proxy