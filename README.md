# 帝焰搬运的脚本

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)
[![GitHub stars](https://img.shields.io/github/stars/li1220/diyan.svg?style=popout&label=Stars)](https://github.com/li1220/diyan/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/li1220/diyan.svg?style=popout&label=Fork)](https://github.com/li1220/diyan/fork)
## 脚本索引
* [***代理相关***](#代理相关)
  * [ssrmu.sh](#ssrmush)
  
  ## 代理相关
## ssrmu.sh

- 脚本说明: ShadowsocksR 一键安装管理脚本，支持流量控制
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: http://cq.diyan.xyz
- 项目地址: https://github.com/li1220/shadowsocksr

#### 脚本特点:
目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

- 支持 限制 用户速度
- 支持 限制 用户设备数
- 支持 限制 用户总流量
- 支持 定时 流量清零
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT

#### 下载安装:
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/li1220/diyan/master/ssrmu.sh&& chmod +x ssrmu.sh && bash ssrmu.sh
```
