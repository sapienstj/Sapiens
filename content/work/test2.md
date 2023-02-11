---
# 文章创建时间
first_date: 2023-01-09 21:32:45

# 最后更新时间
last_date: 2023-02-01 22:22:52

# 草案开关，草案开启将不会转换此文章，true或者false，写完文章务必将其修改为false
draft: false

# 标题
title: "Test2"

# 文章链接字段
slug: "test2"

# 内容描述
description: "测试描述2"

# 标签，用“|”隔开
stack: "test2 | 测试2"

# 外站链接，留空不显示
website_link: "/work/test1"

# github 项目地址，留空不显示
github_link: "https://github.com/kuisec"

# bilibili 视频地址，留空不显示
bilibili_link: "https://www.bilibili.com/video/BV18d4y1j7if"

# 文章索引，索引值越小，优先级越高
index: 2

# 启用图片alpha通道支持，如果开关关闭则表示图像默认会居中裁剪显示，相反图像会居右边缘化显示
img_alpha_support: false

# 封面图片，支持透明，比例最好为16:9
cover_image: "https://th.wallhaven.cc/small/jx/jxx87q.jpg"

# 封面颜色，例如 transparent （透明）或 16进制RGB值，通常从封面图片取色
cover_color: "#c4432e"

# 详情页图片，支持透明，比例最好为4:3
content_image: "https://w.wallhaven.cc/full/jx/wallhaven-jxx87q.jpg"

# 内容块颜色，例如 transparent （透明）或 16进制RGB值，通常提供给透明图片做背景
content_color: "transparent"
---

<div align="center">
<h1>优秀图片展示</h1>
</div>
<table id="imgTable" width="100%">
    <tbody>
        <tr>
            <td>
                <div id="div1" style="background-image: url('https://w.wallhaven.cc/full/rr/wallhaven-rrr7zq.jpg');"></div>
            </td>
            <td>
                <div id="div2"  style="background-image: url('https://w.wallhaven.cc/full/ex/wallhaven-exxogo.jpg');"></div>
            </td>
            <td>
                <div id="div3" style="background-image: url('https://w.wallhaven.cc/full/9d/wallhaven-9dd5yd.jpg');"></div>
            </td>
        </tr>
        <tr>
            <td>
                <div  id="div4" style="background-image: url('https://w.wallhaven.cc/full/l8/wallhaven-l88q5l.jpg');"></div>
            </td>
            <td>
                <div id="div5" style="background-image: url('https://w.wallhaven.cc/full/jx/wallhaven-jxx8mm.jpg');"></div>
            </td>
            <td>
                <div id="div6" style="background-image: url('https://w.wallhaven.cc/full/gp/wallhaven-gppjvd.jpg');"></div>
            </td>
        </tr>
        <tr>
            <td>
                <div id="div7" style="background-image: url('https://w.wallhaven.cc/full/kx/wallhaven-kxx957.jpg');"></div>
            </td>
            <td>
                <div id="div8" style="background-image: url('https://w.wallhaven.cc/full/yx/wallhaven-yxxj3k.jpg');"></div>
            </td>
            <td>
                <div id="div9" style="background-image: url('https://w.wallhaven.cc/full/rr/wallhaven-rrr79j.jpg');"></div>
            </td>
        </tr>
        <tr>
            <td>
                <div id="div10" style="background-image: url('https://w.wallhaven.cc/full/3l/wallhaven-3llk86.jpg');"></div>
            </td>
            <td>
                <div id="div11" style="background-image: url('https://w.wallhaven.cc/full/qz/wallhaven-qzz6gq.jpg');"></div>
            </td>
            <td>
                <div id="div12" style="background-image: url('https://w.wallhaven.cc/full/x6/wallhaven-x66lj3.jpg');"></div>
            </td>
        </tr>
    </tbody>
</table>
<h1 id="dateH1">时间显示</h1>
<script>
    function setStyle() {
        //设置间隔
        var imgTable = document.getElementById("imgTable");
        imgTable.style.width = "100%";
        imgTable.style.borderCollapse = "separate";
        imgTable.style.borderSpacing = "10px 10px";
        //给每一张图片设置顶部向下裁剪填充
        for(var i = 1; i <= 12; i++) {
            var div = document.getElementById("div" + i);
            div.style.width = "width: 30%";
            div.style.height = "500px";
            div.style.backgroundPosition = "top";
            div.style.backgroundRepeat = "no-repeat";
            div.style.backgroundSize = "cover";
            div.style.borderRadius = "0.8rem";
        }
    }
    function displayDate() {
        const time = new Date();
        document.getElementById("dateH1").innerHTML="当前时间为 " + time.getFullYear() + "-" + (time.getMonth() + 1) + "-" + time.getDate() + " " + time.getHours() + ":" + time.getMinutes() + ":" + time.getSeconds();
        setTimeout("displayDate()", 1000);
    }
    setStyle();
    displayDate();
</script>


完结！

