pingpp Android SDK
============

## 简介

lib 文件夹下是 Android SDK 文件，<br>
example 文件夹里面是一个简单的接入示例，该示例仅供参考。<br>
安卓端如果应用没有安装银联支付控件：请到 http://mobile.unionpay.com/getclient?platform=android&type=securepayplugin 下载。

## 版本要求

Android SDK 要求 Android 2.3 及以上版本

## 接入方法

关于如何使用 SDK 请参考 [技术文档](https://pingxx.com/document) 或者参考 [example](https://github.com/PingPlusPlus/pingpp-android/tree/master/example) 文件夹里的示例。

## 更新日志

### 2.0.0
* 更改：<br>
callback 添加返回错误信息

### 1.0.5
* 修复：<br>
微信未登录情况下，点返回，应用无响应，需要再按一次返回才能继续操作

### 1.0.4
* 更改：<br>
更换了测试环境 URL
