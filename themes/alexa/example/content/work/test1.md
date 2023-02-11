---
# 文章创建时间
first_date: 2023-01-12 22:11:23

# 最后更新时间
last_date: 2023-02-01 22:22:52

# 草案开关，草案开启将不会转换此文章，true或者false，写完文章务必将其修改为false
draft: false

# 标题
title: "Test1"

# 文章链接字段
slug: "test1"

# 内容描述
description: "测试描述1"

# 标签，用“|”隔开
stack: "test1 | 测试1"

# 外站链接，留空不显示
website_link: ""

# github 项目地址，留空不显示
github_link: ""

# bilibili 视频地址，留空不显示
bilibili_link: ""

# 文章索引，索引值越小，优先级越高
index: 1

# 启用图片alpha通道支持，如果开关关闭则表示图像默认会居中裁剪显示，相反图像会居右边缘化显示
img_alpha_support: true

# 封面图片，支持透明，比例最好为16:9
cover_image: "https://th.wallhaven.cc/small/p9/p992mp.jpg"

# 封面颜色，例如 transparent （透明）或 16进制RGB值，通常从封面图片取色
cover_color: "#8f6c74"

# 详情页图片，支持透明，比例最好为4:3
content_image: "https://w.wallhaven.cc/full/p9/wallhaven-p992mp.jpg"

# 内容块颜色，例如 transparent （透明）或 16进制RGB值，通常提供给透明图片做背景
content_color: "#6f443b"
---

# Focus-On-Work

## 引用

> Focus-On-Work 是一款高度简洁、注意力集中的主题，其支持 v0.68.3 及以上版本的 Hugo。以下是展示内容。

<br />

## 标题

1. # 一级标题

2. ## 二级标题

3. ### 三级标题

4. #### 四级标题

5. ##### 五级标题

<br />

## 图片（自动圆角）

![image-20230201133648917](https://kuisec.oss-cn-chengdu.aliyuncs.com/kuisec/images/image-20230201133648917.png)

<br />

## 列表

#### 无序列表

- 什么是 [Focus-On-Work](https://github.com/kuisec/focus-on-work.git)？
- 如何使用 [Focus-On-Work](https://github.com/kuisec/focus-on-work.git)?

#### 有序列表

1. 这是第一条
2. 这是第二条

<br />

## 文字板块

文字加粗：**Hello**

文字斜体：*Hello*

文字下划线：<u>Hello</u>

文字删除线：~~Hello~~

公式：$sin^2x = \frac{1}{2}(1 - cos2x)$

代码：`System.out.print("test");`

超链接：[Hello]()

<br />

## 代码块

```java
public void init(int id) {
    System.out.print("init id:" + id);
    String[] init_arr = {"init1",
                        "init2", 
                        "init3", 
                        "init4", 
                        "init5"};
    for(String s : init_arr) {
        System.out.print(s);
    }
}
```
