<div align="center" style="display: flex; flex-flow: column; align-items: center;">
    <img src="https://github.com/Houvven/Guise/blob/31f4e3a84325029750eeca26df77d99b5ac7fc26/assets/ic_launcher-playstore.png" alt="logo" width="150" style="zoom:25%;" />
    <h1>Guise</h1>
    <h5 style="margin-top: -5px;">Put a sheep's skin on your Android app</h5>
    </br>
    <div>
        <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.houvven.guise/total?label=Downloads">
        <img alt="GitHub all releases" src="https://img.shields.io/badge/Android-11 or above-cornflowerblue.svg">
    </div>
</div>




## 描述

Guise是一个对标**应用变量**的[Xposed](https://baike.baidu.com/item/Xposed%E6%A1%86%E6%9E%B6/16859077)模块，其主要作用是为你的安卓设备上的软件传递不同的系统参数。你可以随心所欲的设置它们。

*在Android 13上使用[Lsposed](https://baike.baidu.com/item/LSPosed?fromModule=lemma_search-box)测试通过，未测试其他Android版本以及其他框架。*



## 可配置项

- 品牌
- 型号
- 网络类型
- WiFi-SSID
- WiFi-BSSID
- SIM运营商代码
- SIM运营商
- SIM国家 (iso)
- Android ID (SSAID)
- IMEI
- 位置模拟
- 电量百分比
- 语言
- 强制启用/禁用截屏
- ......
- 更多功能正在路上



## 使用帮助

1. 在[Lsposed](https://github.com/LSPosed/LSPosed)中勾选需要配置的应用进行激活
2. 在本模块中对其进行配置
3. 在配置进行修改后保存且重启所配置的应用😊
