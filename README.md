<img width="768" src="https://github.com/openwrt/openwrt/blob/main/include/logo.png"/>

## 特别提示 [![](https://img.shields.io/badge/-个人免责声明-FFFFFF.svg)](#特别提示-)

- **本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任！**

- **本固件禁止用于任何商业用途，请务必严格遵守国家互联网使用相关法律规定！**

## 项目说明 [![](https://img.shields.io/badge/-项目基本介绍-FFFFFF.svg)](#项目说明-)
- 固件默认管理地址：`192.168.1.1` 默认用户：`root` 默认密码：`password`
- 源码：[LiBwrt](https://github.com/LiBwrt-op/openwrt-6.x)
- 源码：[immortalwrt](https://github.com/immortalwrt/immortalwrt)
- 云编译来源：https://github.com/haiibo/OpenWrt

## 固件下载 [![](https://img.shields.io/badge/-编译状态及下载链接-FFFFFF.svg)](#固件下载-)
点击下表中 [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?style=flat&logo=hack-the-box)](https://github.com/haiibo/OpenWrt/releases) 即可跳转到该设备固件下载页面
| 平台+设备名称 | 固件编译状态 | 配置文件 | 固件下载 |
| :-------------: | :-------------: | :-------------: | :-------------: |
| [![](https://img.shields.io/badge/IPQ60XX-ALL-32C955.svg?logo=openwrt)](https://github.com/breeze303/openwrt-ci/blob/main/.github/workflows/IPQ60XX-ALL.yml) | [![](https://github.com/breeze303/openwrt-ci/actions/workflows/IPQ60XX-ALL.yml/badge.svg)](https://github.com/breeze303/openwrt-ci/actions/workflows/IPQ60XX-ALL.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/breeze303/openwrt-ci/blob/main/configs/ipq60xx-all.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/breeze303/openwrt-ci/releases/IPQ60XX-ALL) |
| [![](https://img.shields.io/badge/IPQ60XX-NOWIFI-32C955.svg?logo=openwrt)](https://github.com/breeze303/openwrt-ci/blob/main/.github/workflows/IPQ60XX-NOWIFI.yml) | [![](https://github.com/breeze303/openwrt-ci/actions/workflows/IPQ60XX-NOWIFI.yml/badge.svg)](https://github.com/breeze303/openwrt-ci/actions/workflows/IPQ60XX-WIFI.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/breeze303/openwrt-ci/blob/main/configs/ipq60xx.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/breeze303/openwrt-ci/releases/IPQ60XX-NOWIFI) |
| [![](https://img.shields.io/badge/IPQ807X-WIFI-32C955.svg?logo=openwrt)](https://github.com/breeze303/OpenWrt/blob/main/.github/workflows/IPQ807X-WIFI.yml) | [![](https://github.com/breeze303/OpenWrt/actions/workflows/IPQ807X-WIFI.yml/badge.svg)](https://github.com/breeze303/OpenWrt/actions/workflows/IPQ807X-WIFI.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/breeze303/OpenWrt/blob/main/configs/ipq807x-wifi.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/breeze303/OpenWrt/releases/IPQ807X-WIFI) |
| [![](https://img.shields.io/badge/X86-64-32C955.svg?logo=openwrt)](https://github.com/breeze303/openwrt-ci/blob/main/.github/workflows/X86-64.yml) | [![](https://github.com/breeze303/openwrt-ci/actions/workflows/X86-64.yml/badge.svg)](https://github.com/breeze303/openwrt-ci/actions/workflows/X86-64.yml) | [![](https://img.shields.io/badge/编译-配置-orange.svg?logo=apache-spark)](https://github.com/breeze303/openwrt-ci/blob/main/configs/x86-64.config) | [![](https://img.shields.io/badge/下载-链接-blueviolet.svg?logo=hack-the-box)](https://github.com/breeze303/openwrt-ci/releases/tag/X86-64) |


## 定制固件 [![](https://img.shields.io/badge/-项目基本编译教程-FFFFFF.svg)](#定制固件-)
1. 首先要登录 Gihub 账号，然后 Fork 此项目到你自己的 Github 仓库
2. 修改 `configs` 目录对应文件添加或删除插件，或者上传自己的 `xx.config` 配置文件
3. 插件对应名称及功能请参考恩山网友帖子：[Applications 添加插件应用说明](https://www.right.com.cn/forum/thread-3682029-1-1.html)
4. 如需修改默认 IP、添加或删除插件包以及一些其他设置请在 `diy-script.sh` 文件内修改
5. 添加或修改 `xx.yml` 文件，最后点击 `Actions` 运行要编译的 `workflow` 即可开始编译
6. 编译大概需要3-5小时，编译完成后在仓库主页 [Releases](https://github.com/haiibo/OpenWrt/releases) 对应 Tag 标签内下载固件

如果你觉得修改 config 文件麻烦，那么你可以点击此处尝试本地提取 https://github.com/LiBwrt/openwrt-6.x

**如果看不懂编译界面可以参考 YouTube 视频：[软路由固件 OpenWrt 编译界面设置](https://www.youtube.com/watch?v=jEE_J6-4E3Y&list=WL&index=7)**


<a href="#readme">
<img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" title="返回顶部" align="right"/>
</a>
