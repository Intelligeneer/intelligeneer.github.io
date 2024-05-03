+++
title = '旧版网店修改'
categories = ["POSPAL", "Training"]
tags = ["Internal_Use"]
date = 2024-04-26
draft = false
author = 'Chris'
weight = 2 # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
password = "lovedaisy"
+++

[新版网店修改跳转链接](../new_ver_website/)

**以下我们拿测试账号测试**

```url
首先需要在后台 ---> 设置 ---> 基础设置 ---> 访问地址：https://bzmw9-28.pospal.cn
```
![storewebsite.png](/img/storewebsite.png)

**下一步，将访问地址复制到浏览器里面，并添加后缀 wkb/customize/editcss**
```url
https://bzmw9-28.pospal.cn/wkb/customize/editcss
```
**然后登入银豹的账号和密码，登入完成后再将上面的网站放入浏览器中**

```css
/* 头部颜色 */
#categoriesView .yb-header-home {
    background: #cb3038;
    color: #fff;
}
/* 左侧边栏项目 (自助模式二维码)*/
.yb-deals_tpl_4 .yb-deals_left .yb-item {
    color: #fff;
    background: #004b9e;
}
/* 登陆按钮 */
.yb-header-home .yb-person-lnk{
 display: none
}
/* 搜索按钮图片 */
.yb-header-home .yb-search-lnk img {
    content: url(//imgw.pospal.cn/we/weidian/img/iconsV2/searchWhite.png);
}

/* 套餐商品名 */
.yb-package-wrapper .yb-package-product_name {
    white-space: pre-wrap; 
    height: 4rem;
}

/* 隐藏优惠卷 */	
#showCouponSelects {
    Display:none
}

/* 左侧边栏项目 (桌码模式) */

.yb-deals_tpl_4 .yb-deals_left .yb-item,
.yb-deals_tpl_1 .yb-deals_left .yb-item {

    color: #ffffff;

    background: #8B0000;

}
```


***这是一些比较基础的修改方式，如果需要更高阶的，请联系李辉***

