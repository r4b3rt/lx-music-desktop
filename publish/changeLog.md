如果你喜欢并经常使用洛雪音乐，并想要第一时间尝鲜洛雪的新功能，可以加入测试企鹅群768786588，
注意：测试版的功可能会不稳定，打算潜水的勿加。

### 新增

- 歌曲搜索框新增清理按钮，点击此按钮可以清理搜索框并返回初始搜索界面
- 新增“下载的歌词文件编码格式”设置，默认下载的歌词编码仍是`UTF-8`，对于某些在设备(如车机)上出现歌词中文乱码的用户可以尝试选择以`GBK`编码格式保存歌词文件
- 新增设置-桌面歌词-歌词字体设置，此设置可用于设置桌面歌词的字体（已知的问题：Windows 7 下可能会出现字体列表为空的情况，这是当前系统的 Powershell 版本小于5.1导致的，请自行**尝试**看常见解决）

### 优化

- 支持网易源“我喜欢”歌单以注入token的方式打开。由于网易源的“我喜欢”歌单需要登录才能打开（若你看不懂后半句就去阅读 常见问题-无法打开外部歌单），现若想要打开此类歌单，需要在歌单链接后面拼上 `###` 再加上有效的token，拼接格式：`[id|url]###token`，例子（最后面的xxxxxx替换成你的token）：`https://music.163.com/#/playlist?id=123456&userid=123456###xxxxxx`
- 软件内快捷键的最小化触发时，如果已启用托盘，则隐藏程序，否则最小化程序

### 修复

- 修复某些情况下同步功能会导致切歌混乱的问题
