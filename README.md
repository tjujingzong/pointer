# 点名器

英语老师让我写一个随机点名的软件，于是乎...

## 本项目优点

快速部署，一个fork后利用GithubPage进行**在线使用**

## 如何使用

- 在线使用

1. 点击本页面右上角fork即可
2. 启用 GitHub Pages 在你 fork 的仓库的主页面上，点击“Settings”（设置）。
向下滚动到“GitHub Pages”部分。
在“Source”（源）下拉菜单中，选择一个发布源。如果你的网站文件位于仓库的根目录中，则通常选择“master branch”或“main branch”。
一旦选择了分支，页面将刷新，并显示一个绿色的消息框，其中包含你的网站URL。

3. 访问你的网站
使用在“GitHub Pages”设置中提供的URL访问你的网站。URL通常的格式是 https://{username}.github.io/{repository}，其中 {username} 是你的GitHub用户名，{repository} 是仓库的名字。

注意！！！！ 因为此处仓库的名字是pointer 对./_includes/head.html中存储路径要做出修改

![image](https://github.com/tjujingzong/pointer/assets/88825933/e6b56260-d89f-4a16-9d5f-ad5c61c55940)

- 离线使用

1. 下载本项目

```bash
# 下载项目
git clone git@github.com:Himself65/pointer.git 
```

或者下载压缩包也可以

2. 安装所需库

```bash
gem install jekyll
```

3. 运行

```bash
cd pointer

jekyll serve
```

## LICENSE

[MIT LICENSE](./LICENSE)
