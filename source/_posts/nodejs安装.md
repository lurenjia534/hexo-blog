---
title: nodejs安装
---
###### 🍋前言:记录一次nodejs与npm安装，我在Github找到了现成的安装方案  

---
**[项目地址](https://github.com/nodesource/distributions#debinstall)**  

###### 安装16.x的版本(目前最新)  

```bash
# Using Ubuntu
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
apt-get install -y nodejs
```

###### 安装14.x的版本(目前最新)  

```bash
# Using Ubuntu
curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -fsSL https://deb.nodesource.com/setup_14.x | bash -
apt-get install -y nodejs
```

---

###### 后记:🍋这样npm和nodejs全部安装完毕~🍎
