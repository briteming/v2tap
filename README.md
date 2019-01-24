[![](https://img.shields.io/badge/%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F-Telegram-blue.svg)](https://t.me/Holli_Freed)

# v2tap
基于 TUN/TAP + tun2socks + v2ray 实现的 VPN 工具

推一下自己项目：[v2ray-installers](https://github.com/hacking001/v2ray-installers)

# TODO
- [ ] 给 v2tap 上一个图标
- [ ] 本地 DNS 代理（目前考虑 DoH 来拒绝污染，也支持普通 UDP 查询代理）
- [ ] 为 mKCP 和 QUIC 添加伪装支持
- [x] 像 SSTap 那样搞一个规则列表？
- [x] 流量信息显示（当前上传/下载速度和已使用总流量）
- [x] 订阅链接保存

# 依赖文件
- [TAP Windows](https://build.openvpn.net/downloads/releases/latest/tap-windows-latest-stable.exe)
- [v2ray-core](https://github.com/v2ray/v2ray-core/releases)
- [tun2socks](https://github.com/hacking001/v2tap/tree/master/binaries)

# 准备工作
1. 从 [releases](https://github.com/hacking001/v2tap/releases) 中下载最新版的包
2. 安装 `tap-windows-latest-stable.exe`，请务必一路 next，不懂请不要乱点
3. 可用的 v2ray 服务器（暂时不支持伪装）

# 正式开始
1. 打开 `v2tap.exe` 点击添加按钮增加一个配置信息

![](screenshots/one.png)

![](screenshots/two.png)

2. 选择新添加的配置信息

![](screenshots/three.png)

3. 检查 [Google](https://www.google.com/ncr) 是否可以正常访问

![](screenshots/four.png)
