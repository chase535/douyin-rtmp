

# 抖音直播推流地址获取工具

一款基于python3.12开发、Npcap进行网络抓包的抖音直播推流地址获取工具

## 使用说明

### 使用环境
Windows 10 及以上版本

### 使用说明

1. 本工具使用了网络抓包技术，可能会被杀毒软件误报，在下载时请关闭所有的杀毒软件，如360、腾讯管家、火绒、windows defender等;
2.  在[Releases](https://github.com/heplex/douyin-rtmp/releases)页面下载最新版本的抖音直播推流地址获取工具，或直接下载本仓库中的`dist/抖音直播推流地址获取工具v1.0.0.exe`
3. 下载完成后，使用管理员权限进行运行；
4. 在弹出的免责声明对话框中，点击“确定”按钮，继续使用则表示您同意以上条款；
5. 如果未检测到Npcap，会提示先安装Npcap，安装完成后，重新启动软件；
6. 选择对应的网络接口，有线网卡优先，如果未检测到，请手动选择；
7. 点击“开始捕获”按钮，开始捕获抖音直播推流地址；
8. 打开直播伴侣进行开播，推流地址会自动获取，并显示在软件中；
9. 如果推流地址获取失败，请检查网络接口是否选择正确，以及直播伴侣是否正常开播；
10. 如果仍然失败，可以尝试在工具重新安装Npcap，并重新启动软件；

### 卸载

1. 在工具选项下，点击卸载Npcap，卸载完成后，删除本软件即可；



## 免责说明

1. 本工具仅供学习和研究使
2. 请勿用于任何商业用途
3. 使用本工具产生的一切后果由使用者自行承担
4. 本工具使用了网络抓包技术，可能会被杀毒软件误报
   这是因为抓包功能与某些恶意软件行为类似，请放心使用

## 界面展示

### 使用界面

![使用界面](./images/使用界面.png)

## 更新日志

1. 2025.01.06 更新获取推流地址以及推流功能


## 开发指南

打包命令：
```
pyinstaller --onefile --uac-admin --add-data resources;resources --noconsole main.py
```



## Star History

<a href="https://star-history.com/#heplex/douyin-rtmp&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=heplex/douyin-rtmp&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=heplex/douyin-rtmp&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=heplex/douyin-rtmp&type=Date" />
 </picture>
</a>

