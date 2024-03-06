# Knowledge Graphs Report
## Lab. 3: publishing data

### TTL File

After using ```curl -I https://hgomlop.github.io/NewturtleFile.ttl``` the result is:
```
HTTP/2 200 
server: GitHub.com
content-type: text/turtle; charset=utf-8
permissions-policy: interest-cohort=()
last-modified: Wed, 06 Mar 2024 18:37:28 GMT
access-control-allow-origin: *
strict-transport-security: max-age=31556952
etag: "65e8b7e8-395"
expires: Wed, 06 Mar 2024 20:12:27 GMT
cache-control: max-age=600
x-proxy-cache: MISS
x-github-request-id: 3D3E:301FA4:15A3A3D:16070E9:65E8CBD3
accept-ranges: bytes
date: Wed, 06 Mar 2024 20:02:27 GMT
via: 1.1 varnish
age: 0
x-served-by: cache-ams21042-AMS
x-cache: MISS
x-cache-hits: 0
x-timer: S1709755348.728130,VS0,VE114
vary: Accept-Encoding
x-fastly-request-id: 9ea2689fda02b1e1e32cfd8ff9b7df4bb3415b22
content-length: 917
```

### JSON-LD File

After using ```curl -I https://hgomlop.github.io/NewjsonFile.jsonld``` the result is:
```
HTTP/2 200 
server: GitHub.com
content-type: application/ld+json
permissions-policy: interest-cohort=()
last-modified: Wed, 06 Mar 2024 18:37:28 GMT
access-control-allow-origin: *
strict-transport-security: max-age=31556952
etag: "65e8b7e8-3ff"
expires: Wed, 06 Mar 2024 20:05:29 GMT
cache-control: max-age=600
x-proxy-cache: MISS
x-github-request-id: F7E4:3A52AE:4403F0:45150E:65E8CA2B
accept-ranges: bytes
date: Wed, 06 Mar 2024 19:55:29 GMT
via: 1.1 varnish
age: 0
x-served-by: cache-ams21057-AMS
x-cache: MISS
x-cache-hits: 0
x-timer: S1709754929.223893,VS0,VE108
vary: Accept-Encoding
x-fastly-request-id: f2e37ea8f1a025f407e176c337d1629a90f23dbb
content-length: 1023
```