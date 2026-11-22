# AMap CocoaPods Specs

高德 iOS SDK 的独立 CocoaPods Specs 源，podspec 保留上游内容，SDK 二进制仍由高德官方地址下载。

包含 AMapNavi 11.3.100、AMap3DMap 11.3.100、AMapLocation-NO-IDFA 2.12.2、AMapSearch-NO-IDFA 9.8.1，以及 AMapFoundation / AMapFoundation-NO-IDFA 1.9.4。

导航包已包含地图功能，请勿在同一个 target 同时集成 AMapNavi 和 AMap3DMap。基础库 IDFA 与 NO-IDFA 版本也不可混用。

目录采用 PodName/Version/PodName.podspec.json，可作为普通 Git Specs repo 使用。
