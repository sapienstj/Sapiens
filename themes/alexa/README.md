<div align="center">
	<h1>Focus On Work</h1>
</div>



适用于作为主页的 Hugo 响应式主题（Hugo Theme），对移动端的支持十分友好，主题简洁明了，便于展示和集中注意力。

此 Readme.md 对应主题版本为 v2.0.2。

### 来源
本主题为二次修改与创作，源主题作者为 [Bonzdev](https://github.com/Bonzdev/alexa-portfolio) ，国外的审美一直都比较优雅，所以我认为这么优秀的主题不应该没落，于是我将其更改为对国人和新手小白更友好的中文界面，并修复了一些原作者并未发现的bug，增加了对国人更友好的图片显示方式以及优化了界面状况。

### Demo
- [Demo Website](https://focus-on-work.netlify.app/)
- [My Website](https://www.kuisec.net)

<br />

## Hugo 版本要求

- Hugo 版本至少为 <font color="red">0.68.3 或更高</font>

<br />

## 如何使用这个主题

- [克隆或下载主题](#克隆或下载主题)
- [使用主题](#使用主题)

<br />

## 克隆或下载主题

### 使用 Hugo 创建站点（可选）

打开 Windows CMD，输入以下命令创建一个网站，若你已存在网站，可以跳过这个步骤（<font color="red">请注意，在运行此命令前，你应该将 Hugo 可执行文件设置为全局变量</font>）。

```bash
hugo new site 你的站点名称
```

### 获得主题（通过下载）

在 github 上项目页点击绿色 `Code` 按钮，在按钮下方的弹窗中选择 `Download ZIP` 选项。选择完毕之后，将其复制到站点的 `themes` 目录下，并修改其文件夹名称为 `focus-on-work` 。

### 获得主题（通过 git 工具）

进入站点所在的 `themes` 目录下，运行以下命令：

```bash
git clone https://github.com/kuisec/focus-workhttps://github.com/kuisec/focus-on-work.git focus-on-work
```

<br />

## 使用主题

为了方便理解，我将假设目前的站点文件夹为 www。

### 复制配置文件

将 `www\themes\focus-on-work\example\config.toml` 复制到 `www` 根目录。<font color="red">警告：此操作会覆盖你之前创建的配置文件，在进行此操作之前，请将你之前的 config.toml 文件备份。</font>

将 `www\themes\focus-on-work\example\content` 文件夹下所有 .md 文件复制到 `www\content` 对应的文件夹中。

### 查看效果

打开 Windows CMD，将路径调整到站点文件夹，运行以下命令（<font color="red">请注意，在运行此命令前，你应该将 Hugo 可执行文件设置为全局变量</font>）：

```bash
hugo server -p 1313
```

打开浏览器，输入 `localhost:1313` 来查看网站生成内容。

### 创建新文章

#### 使用主题模板创建文章

在创建新文章之前，请先将路径为 `站点根路径\archetypes` 的文件夹删掉。然后打开 Windows CMD，将路径调整到站点文件夹，运行以下命令（<font color="red">请注意，在运行此命令前，你应该将 Hugo 可执行文件设置为全局变量</font>）：

```bash
hugo new /work/文章名称.md
```

#### 如需创建空白文章，请键入下面命令

```bash
hugo new /work/文章名称.md -k empty
```

<br />

## 问题

如果你有问题或是更好的提议，请打开 [issue](https://github.com/kuisec/hugo-theme-kuisec/issues) 面板来得到更多帮助。

<br />

## 贡献

如果你也想参加贡献，那么可以动动小手点击 Fork 即可，如果修改合适，我会及时通过并合并！

<br />

## 许可证

本项目此前由 [Bonzdev](https://github.com/Bonzdev/alexa-portfolio) 移植，受 [MIT](BEFORE_LICENSE) 保护和约束。
目前此项目增加了 [AGPL-3.0](LICENSE) 许可证，请确保你的使用不会违反此许可条例。

<br />

## 🤝 支持

如果你喜欢本主题，还望给予一颗小小的 ✨✨✨。
如果你认为我的工作做得还不错，那么请我喝杯可口可乐啵！😊💕👍😍

<div align="center" style="width: 100%; height: auto; background-image: url('https://w.wallhaven.cc/full/x6/wallhaven-x66lj3.jpg"></div>

