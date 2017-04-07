# easy-proxy

If you want to proxy something you just run 
```
docker run --rm -p 8000:80 -e REMOTE=http://google.com easy-proxy
```
And now if you go to http://localhost:8080 you have google behind a proxy.

