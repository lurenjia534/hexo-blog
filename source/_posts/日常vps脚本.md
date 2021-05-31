---
title: 日用vps脚本
---
前言:日常需要的vps比较杂乱打算自己整理一下

---
### 各类脚本
###### 秋水大佬编写的VPS信息查看脚本
```bash
wget -qO- bench.sh | bash
#或者
curl -Lso- bench.sh | bash
#或者
wget -qO- 86.re/bench.sh | bash
#或者
curl -so- 86.re/bench.sh | bash
```
---
###### v2ray搭建脚本，多合一，胜在方便
```bash
bash <(curl -sL https://s.hijk.art/v2ray.sh)
```
---
###### 逗逼聚集地的大佬的ssr脚本
```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```
###### MTProxy TLS 脚本
```bash
mkdir /home/mtproxy && cd /home/mtproxy
curl -s -o mtproxy.sh https://raw.githubusercontent.com/ellermister/mtproxy/master/mtproxy.sh && chmod +x mtproxy.sh && bash mtprox
```
```bash
bash mtproxy.sh start 开始
bash mtproxy.sh stop 停止
bash mtproxy.sh restart 重启
```

