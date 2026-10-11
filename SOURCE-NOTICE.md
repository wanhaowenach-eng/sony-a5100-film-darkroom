# 来源与组件说明

胶片暗房0.8b：本地验收版本，APK SHA256固定为0afab54dd97f4a4ff3fea3236f19bb5d81d95db584177bdf7a6adcb05090ea23。原APK未重新编译。

源码快照见source-0.8b。胶片工坊滤镜参考项目：https://github.com/ukiki0718-netizen/sony-a5100-film-studio 。继承的开源模块按各自许可处理。原应用框架、Sony专有接口及JNI组件仍属于各自权利人；不能把整个APK笼统声明为MIT/LGPL开源，源码快照也不授予Sony组件的额外再分发权。本包不包含独立的付费Sony应用安装包或固件。

PMCA v0.18：https://github.com/ma1co/Sony-PMCA-RE/releases/tag/v0.18 ，MIT，见licenses。
Tweak v0.11：https://github.com/ma1co/OpenMemories-Tweak/releases/tag/v0.11 ，MIT，见licenses。
ADB来自Google Platform Tools，本地版本见platform-tools/source.properties，第三方声明见platform-tools/NOTICE.txt，来源https://developer.android.com/tools/releases/platform-tools 。

首次安装器为本次新增，不依赖早期RAW应用；APK包含运行所需的MemoryUtil JNI库。Sony系统接口仍由相机提供。新安装器未在另一台空白相机上真机验证。
