---
title: 日用vps脚本
---
🍋前言:日常需要的vps比较杂乱打算自己整理一下

---
### 各类脚本
###### 秋水大佬编写的VPS信息查看脚本
```shell
wget -qO- bench.sh | shell
#或者
curl -Lso- bench.sh | shell
#或者
wget -qO- 86.re/bench.sh | shell
#或者
curl -so- 86.re/bench.sh | shell
```
---
###### v2ray搭建脚本，多合一，胜在方便
```shell
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/wulabing/V2Ray_ws-tls_shell_onekey/dev/install.sh" && chmod +x install.sh && shell install.sh
```
```shell
bash <(curl -s -L https://git.io/v2ray.sh)
```
---
###### 逗逼聚集地的大佬的ssr脚本
```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && shell ssr.sh
```
---
###### MTProxy TLS 脚本
```shell
mkdir /home/mtproxy && cd /home/mtproxy
curl -s -o mtproxy.sh https://raw.githubusercontent.com/ellermister/mtproxy/master/mtproxy.sh && chmod +x mtproxy.sh && shell mtprox
shell mtproxy.sh start 开始
shell mtproxy.sh stop 停止
shell mtproxy.sh restart 重启
```

