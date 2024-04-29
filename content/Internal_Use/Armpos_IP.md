+++
title = 'ArmPOS 打印机IP修改'
categories = ["POSPAL", "Training"]
tags = ["Internal_Use"]
date = 2024-04-26
draft = false
author = 'Chris'
weight = 0 # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
+++

***请注意：此打印机只能在带有网线口的Windows上设置***

**自检打印机，查看打印机的IP地址 (如 192.168.123.200)**

**现在去到 Windows 电脑的控制面板 (Control Panel)**
![controlpanel.png](/img/controlpanel.png)

**点开 查看网络状态和任务 (View network status and tasks)**
![internet.png](/img/internet.png)

**点开 更改适配器设置 (Change adapter settings)**
![changeadapter.png](/img/changeadapter.png)

**右键 Ethernet ---> Properties**
![ethernet.png](/img/ethernet.png)

**双击 IPV4**
![ipv4.png](/img/ipv4.png)

**先固定Windows 的IP地址  (如何查看当前电脑IP 地址，CMD 输入 ipconfig)**
![static.png](/img/static.png)

**然后点开 Advanced**
![advanced.png](/img/advanced.png)

**在下面中添加 打印机网段 如：192.168.123.250，添加完成后点确定**
![extraip.png](/img/extraip.png)

**现在 Windows 电脑就可以和打印机通讯了，接下来只要用修改打印机IP的驱动修改打印机即可**
![ethernetprinter.png](/img/ethernetprinter.png)