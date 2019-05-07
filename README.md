wget https://raw.githubusercontent.com/LinIsMySky/Docker/master/docker.sh && chmod +x docker.sh && bash docker.sh
teddysun/shadowsocks-libev:alpine
docker run -d -p 9000:9000 -p 9000:9000/udp --name ss-libev -v /etc/shadowsocks-libev:/etc/shadowsocks-libev teddysun/shadowsocks-libev:alpine
teddysun/shadowsocks-libev:alpine
docker run -d -p 9000:9000 -p 9000:9000/udp --name ss-libev -v /etc/shadowsocks-libev:/etc/shadowsocks-libev teddysun/shadowsocks-libev:alpine
