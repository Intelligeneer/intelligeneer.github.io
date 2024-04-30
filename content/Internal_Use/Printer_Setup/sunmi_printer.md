+++
title = 'Sunmi Cloud Printer IP修改'
categories = ["POSPAL", "Training"]
tags = ["Internal_Use"]
date = 2024-04-26
draft = false
author = 'Chris'
weight = 0 # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
+++

***请注意：此打印机只能在Windows上设置***

[Sunmi 驱动下载链接](https://onedrive.live.com/?cid=8119C2A597679EB1&mid=A0722E84162626D8%21108&mcid=A0722E84162626D8&sd=1&id=8119C2A597679EB1%21130346&parId=8119C2A597679EB1%21130342&o=OneUp "Sunmi驱动下载")

**打开 Sunmi-cloud-printer-setup**
![sunmicloudprinter.png](/img/sunmicloudprinter.png)

**出现提示 点击 More Info**
![noworries.png](/img/noworries.png)

**点击 Run Anyway**
![runanyway.png](/img/runanyway.png)

**将打印机通过自带的USB Type C的线连接到电脑主机，并点击软件上的连接**
![connect.png](/img/connect.png)

**需要同意 Allow**
![allow.png](/img/allow.png)

**看到打印机的信息后，就说明连接成功**
![connected.png](/img/connected.png)


***网线口*的IP地址 ---> IP地址需要先确定是否是可以使用的，检查方法**
```dos
ping 192.168.1.xxx
```
```
子网掩码 255.255.255.0
```
**修改完成后，点击保存即可**
![ethernetipconnect.png](/img/ethernetipconnect.png)

***WiFi*连接并设置IP地址 ---> 需要先连接店内WiFi**
![setssid.png](/img/setssid.png)

![wifinameandpw.png](/img/wifinameandpw.png)
***(P.S. 一定要输入正确的WiFi名)***

**固定WiFi IP，检查可用IP地址方法同上，点击保存**
![wifiip.png](/img/wifiip.png)

**并打印测试页检查IP是否设置成功**
![printertest.png](/img/printertest.png)

**Q.如果这台打印机无法打印简体中文怎么办？**
**去到 *打印设置* ---> UTF-8 改成 *否* ---> 并选择 *GB18030* ---> 然后保存**
![utf8.png](/img/utf8.png)

**打印自检页 ---> 双击后面按键 如图**
![selftest.png](/img/selftest.png)