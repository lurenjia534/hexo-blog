---
title: 日常vps脚本
---
###### 🍋日用VPS脚本集合
---
###### cloud torrent脚本
```
 wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/cloudt.sh && chmod +x cloudt.sh && bash cloudt.sh
```
---
###### v2ray脚本
```
bash <(curl -s -L https://git.io/v2ray.sh)
```
---
###### 秋水逸冰大佬的写的Bench.sh脚本
```
wget -qO- bench.sh | bash
#或者
curl -Lso- bench.sh | bash
#或者
wget -qO- 86.re/bench.sh | bash
#或者
curl -so- 86.re/bench.sh | bash
```
---
###### 老鬼大佬的SuperBench测试脚本
```
wget -qO- --no-check-certificate https://raw.githubusercontent.com/oooldking/script/master/superbench.sh | bash
#或者
curl -Lso- -no-check-certificate https://raw.githubusercontent.com/oooldking/script/master/superb
```
---
###### MTP代理
```
curl -s -o mtproxy.sh https://raw.githubusercontent.com/ellermister/mtproxy/master/mtproxy.sh && chmod +x mtproxy.sh && bash mtproxy.sh
```
```
bash mtproxy.sh start #启动
bash mtproxy.sh stop #停止
bash mtproxy.sh restart #重启
```
---
###### 流媒体解锁检测脚本
```
yum install curl -y #Centos依赖
apt-get update && apt-get install curl #Ubuntu/Debian依赖
apk update && apk add curl #Alpine依赖
```
```
bash <(curl -sSL "https://github.com/CoiaPrant/MediaUnlock_Test/raw/main/check.sh")
```
---