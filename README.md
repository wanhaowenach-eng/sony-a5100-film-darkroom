# 胶片暗房0.9（公开试用）

Sony a5100机内RAW后期工具：选择已有ARW / RAW+JPEG，应用15款滤镜和调色，另存JPEG到原生相册，保留源RAW。非Sony官方应用。

## 下载与安装

### [直接下载胶片暗房0.9 APK（推荐）](https://github.com/wanhaowenach-eng/sony-a5100-film-darkroom/releases/download/v0.9/FilmDarkroom-0.9.apk)

**已有相机应用安装工具：选择这个APK直接安装即可。** 不必下载旧安装ZIP，也不必额外安装Tweak或ADB。

第一次安装：**PMCA → 相机USB设为MTP → 选择APK → 安装**。详细步骤见 [简明安装教程](安装教程.md)。Wi-Fi ADB仅作为已有相应环境时的备用方式。

[0.9发布页与校验文件](https://github.com/wanhaowenach-eng/sony-a5100-film-darkroom/releases/tag/v0.9)。源码ZIP供开发者使用，普通用户安装只需要APK与可用的安装工具。

## 功能

- 15款滤镜，亮度、对比度、饱和度调节。
- RAW / RAW+JPEG选片预览，24M / 12M / 6M JPEG输出。
- 原生相册回放、EXIF及成片管理，保留源照片。
- 触屏与方向键、上次滤镜记忆、按需分页选片、经典暗房图标。

## 版本与验证范围

对外名称及APK内部版本统一为0.9。此前基础版在Sony a5100 / ILCE-5100、固件3.10上获用户使用验证；本次只变更版本号，处理代码与原版一致，签名和完整性检查通过，尚未重新安装验收。其他机型、固件及大量照片的实机跨页尚未充分验证，继续作为公开试用。

可覆盖同包名、同签名的bridge基础版。原始旧0.8b包名不同，继续保留。签名报错请先反馈，不要自动卸载旧应用。

## 源码、许可与反馈

发布页提供 `FilmDarkroom-0.9-Source.zip`，包含对应可编辑源码、重建脚本和历史许可。各组件分别适用原许可，部分继承滤镜参数的再分发授权仍在核查，详见 [SOURCE-NOTICE.md](SOURCE-NOTICE.md)。

反馈请提供机型、固件、安装工具、操作步骤与错误文字。不需要上传照片、视频、真实IP或原始设备日志。
