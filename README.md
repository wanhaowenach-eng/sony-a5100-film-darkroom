# 胶片暗房

Sony a5100 机内 RAW 后期工具。选择已有 ARW / RAW+JPEG，应用滤镜与调色，另存 JPEG 到原生相册，保留源 RAW。非 Sony 官方应用。

## 下载与安装

**[下载经典图标版 0.8b（公开试用）](https://github.com/wanhaowenach-eng/sony-a5100-film-darkroom/releases/tag/v0.8b-bridge8-icon)**

Windows 用户下载 Release 的 `FilmDarkroom-Bridge8-NewUser-Windows.zip`，完整解压后打开 `安装教程.html`。不要把 GitHub 自动生成的 Source code ZIP 当作安装包。

- [在线安装教程](安装教程.md)：MTP、PMCA、OpenMemories: Tweak 与 Wi-Fi ADB 安装步骤。
- 安装包包含 APK、安装脚本、PMCA / Tweak、许可说明与 `Source-Review.zip`。Google ADB 按教程从官方单独下载。
- 无需先安装胶片工坊或旧测试版，不需要修改固件。
- 安装包 SHA256：`c8dbc0b6476430e13d7d61a78c117ec4521aeac8ab32d510d5957c7033f583f5`。

## 功能

- RAW / RAW+JPEG 选片与缩略图，15 款滤镜，亮度、对比度、饱和度调节。
- 24M / 12M / 6M JPEG 输出，支持原生相册回放、EXIF 和成片管理。
- 触屏及方向键操作，记忆上次选择的滤镜。
- 按需加载照片索引，每批最多 96 项，取消原来的 768 项截断。计数后的 `+` 表示尚有记录未读取。
- 经典暗房图标、中文名称与不透明背景。新版对比度 +5 对应此前 +6，0 和负值保持不变。

## 版本与验证范围

当前内部版本：`0.8b-bridge8-icon`。已在 **Sony a5100 / ILCE-5100、固件 3.10、Windows** 环境试用，用户反馈本版无异常。其他机型、固件未验证。

分页模拟检查覆盖 5000 项和跨批次增删；大量照片的实机跨页仍待更多验证。已浏览文字索引保留，不承诺无限内存容量。另一台空白相机的完整首次安装流程尚未实测。

可覆盖 bridge2 至 bridge7 候选版。原始 0.8b 的包名不同，可并存；同名时用红色安全灯图标辨认新版。不建议自动卸载旧应用解决签名不一致。

## 源码、许可与反馈

对应可编辑源码和重建说明位于安装包内 `Source-Review.zip`。源码重建的 DEX、独立桥接库、Manifest 与图标资源已和发布 APK 比对一致；这不表示所有模块共用一个许可证。

各组件适用各自许可，部分继承滤镜参数的再分发授权仍在核查。请阅读 [SOURCE-NOTICE.md](SOURCE-NOTICE.md) 和源码包中的历史许可记录。旧 Sony 应用原生库及旧资源已移除，相机自身仍需 Scalar 系统接口。

反馈请提供机型、固件、版本、操作步骤和屏幕错误文字。无需上传照片、视频、真实 IP 或原始设备日志。
