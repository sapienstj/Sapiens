---
# 文章创建时间
first_date: {{ .Date | time.Format "2006-01-02 15:04:05" }}

# 最后更新时间
last_date: {{ .Date | time.Format "2006-01-02 15:04:05" }}

# 草案开关，草案开启将不会转换此文章，true或者false，写完文章务必将其修改为false
draft: true

# 标题
title: "{{ replace .TranslationBaseName "-" " " | title }}"

# 文章链接字段
slug: "{{ .BaseFileName }}"

# 内容描述
description: ""

# 标签，用“|”隔开
stack: ""

# 外站链接，留空不显示
website_link: ""

# github 项目地址，留空不显示
github_link: ""

# bilibili 视频地址，留空不显示
bilibili_link: ""

# 文章索引，索引值越小，优先级越高
index: 1

# 启用图片alpha通道支持，如果开关关闭则表示图像默认会居中裁剪显示，相反图像会居右透明化显示
img_alpha_support: false

# 封面图片，支持透明，比例最好为16:9
cover_image: ""

# 封面颜色，例如 transparent （透明）或 16进制RGB值，通常从封面图片取色
cover_color: "transparent"

# 详情页图片，支持透明，比例最好为4:3
content_image: ""

# 内容块颜色，例如 transparent （透明）或 16进制RGB值，通常提供给透明图片做背景
content_color: "transparent"
---

