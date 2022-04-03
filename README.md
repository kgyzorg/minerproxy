
<h1 align="center">
  <br>
  <img src="https://cdn.jsdelivr.net/gh/kgyzorg/minerproxy@main/top.png" width="350"/>
</h1>


<h4 align="center">

              ___  ____                ______                    
              |  \/  (_)               | ___ \                   
              | .  . |_ _ __   ___ _ __| |_/ / __ _____  ___   _ 
              | |\/| | | '_ \ / _ \ '__|  __/ '__/ _ \ \/ / | | |
              | |  | | | | | |  __/ |  | |  | | | (_) >  <| |_| |
              \_|  |_/_|_| |_|\___|_|  \_|  |_|  \___/_/\_\\__, |
                                                            __/ |
                                                           |___/ 
</h4>



<h1 align="center">全新界面，支持ETH，ETC，抽水稳定不掉线，作者抽水千分之二。</h1>
<h4 align="center">最稳定的ETH以太坊代理中转矿池程序，MinerProxy/矿池代理，支持TCP和SSL协议，支持自定义抽水，高性能高并发，支持web界面管理，包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定。</h4>

<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-1.0.1_ETHASH-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_04_3-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Language-GoLang-green.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Minerproxy-Kgyz.org-green.svg" alt="travis">
  </a>
</p>

![MinerProxy](https://cdn.jsdelivr.net/gh/kgyzorg/minerproxy@main/p1.jpg)

# 重要提示必看
#### 1.Linux系统第一次安装完成后请重启服务器，这样可以突破连接限制，单机稳定2000台！！！
#### 2.安装完成后，请立即修改默认密码，以防别有用心之人，扫描端口偷偷登录！！！

# MinerProxy - 使用后算力截图，算力几乎无损耗。

![MinerProxy](https://cdn.jsdelivr.net/gh/kgyzorg/minerproxy@main/p2.jpg)
![MinerProxy](https://cdn.jsdelivr.net/gh/kgyzorg/minerproxy@main/p3.jpg)

# 矿工交流 TG电报群：https://t.me/Miner_Proxy
### 联系我们：
[Telegram 讨论群组(欢迎向我们提出建议)](https://t.me/+VR_Ri2OfBnwyNWRh)
[GitHub](https://github.com/MinerPr0xy/MinerProxy) 


# Windows版本
### 最新版下载地址：1.0.1 
###  https://github.com/kgyzorg/minerproxy/releases/download/1.0.1/Kgyz_win_1.0.1.exe


# Windows-使用方法
```bash
运行
Kgyz_win_1.0.1.exe

1、自动初始化  默认密码123456

2、手动设置  自己设置端口和密码


```


# linux 安装说明

```bash
mkdir /home/mtgproxy
wget -P /home/mtgproxy/ https://github.com/xpkill/mtgproxy/releases/download/v1.0.0/mtgproxy_linux_amd64.7z
```
或

```bash
curl -o /home/mtgproxy/mtgproxy_linux_amd64.7z https://ghproxy.com/https://github.com/xpkill/mtgproxy/releases/download/v1.0.0/mtgproxy_linux_amd64.7z
cd /home/mtgproxy
tar -zxvf mtgproxy_linux_amd64.7z
chmod 777 mtgproxy
```


### 首次初始化
```bash
./mtgproxy 
```
1、自动初始化
2、手动设置
->
#默认 端口 23456
http://localhost:23456

### 后台 运行行程序
```bash
sh run.sh
```

### 加入开机运行 修改/etc/rc.local 
```bash
vim /etc/rc.local
```
### 加入下面
```bash
sh /home/mtgproxy/run.sh
```





