Gl-inet AXT1800 固件 + 官方ui


## 固件相关

编译配置文件参考了[JiaY-shi](https://github.com/JiaY-shi)的[build-gl.inet](https://github.com/JiaY-shi/build-gl.inet)，以及[monw](https://github.com/monw)的[gl-infra-builder](https://github.com/monw/gl-infra-builder)

此固件基于[gl-inet](https://github.com/gl-inet)的官方开源仓库[gl-infra-builder](https://github.com/gl-inet/gl-infra-builder)，属openwrt 21.02，4.X内核。


## Openwrt配置相关

- 默认管理页面: 192.168.8.1

- LUCI界面默认使用argon主题

- 集成Openclash，不过并不能在官方固件显示，只能去到luci界面查看

- 添加istore，需要什么应用自己安装

## 关于自动编译脚本

自动编译脚本源自[P3TERX](https://github.com/P3TERX)/[Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

脚本使用说明：[English](https://github.com/P3TERX/Actions-OpenWrt) | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)
