# docker-openresty
openresty dockerfile with lua-openssl

```
./build.sh

docker run -d --name="yourappname" -p 8080:80 -v /yourdir:/nginx openresty
```
