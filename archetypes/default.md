+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
lastmod = {{ .Date }} #更新时间
description = "" #描述
weight = 0 # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
draft = false # 是否为草稿
comments = true #是否展示评论
showToc = true # 显示目录
TocOpen = true # 自动展开目录
hidemeta = false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare = true # 底部不显示分享栏
showbreadcrumbs = true #顶部显示当前路径
+++