<h1 align="center">小米路由器Singbox裸核使用教程</h1>
<p align="center">
  在小米路由器上使用Singbox裸核配合Tproxy入站,实现局域网透明代理
</p>

<p align="center">
  <a href="README_CN.md">简体中文</a> | English
</p>

---
## TODO List
- 1.解锁路由器SSH,执行软固化  
- 2.上传Singbox核心,以及配置文件  
- 3.编写启动脚本,防火墙规则  

---
## 1.SSH解锁
推荐使用Xmir-patcher项目一键解锁  
[Xmir-patcher](https://github.com/openwrt-xiaomi/xmir-patcher)  

1️⃣下载解压后运行`Run.bat`  
2️⃣选择2,等待几秒钟,出现**SSH is already running**则SSH开启成功  
3️⃣选择6,进行**SSH软固化**

---
## 2.上传文件  
下载并安装WinSCP  [WinSCP](https://winscp.net/eng/download.php)
