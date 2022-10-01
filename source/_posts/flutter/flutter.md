---
title: Flutter
date: 2022-10-01 17:52:56
tags: [Flutter]
categories: 书单
cover: http://qn.images.lhqmm.com/wikis/flutter.png
top_img: http://qn.images.lhqmm.com/wikis/flutter.png
---



## Flutter简介
### 极速构建漂亮的原生应用
Flutter是谷歌的移动UI框架，可以快速在iOS和Android上构建高质量的原生用户界面。 Flutter可以与现有的代码一起工作。在全世界，Flutter正在被越来越多的开发者和组织使用，并且Flutter是完全免费、开源的。

## Flutter的安装
1. 安装Git工具，因为获去Flutter需要Git命令
2. 获取Flutter : git clone -b beta https://github.com/flutter/flutter.git
3. 配置环境变量
a. 临时变量：
~~~
export PUB_HOSTED_URL=https://pub.flutter-io.cn //国内用户需要设置
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn //国内用户需要置
export PATH=`pwd`/flutter/bin:$PATH
~~~
b. 永久变量：
转到 “控制面板>用户帐户>用户帐户>更改我的环境变量”
在“用户变量”下检查是否有名为“Path”的条目:
如果该条目存在, 追加 flutter\bin的全路径，使用 ; 作为分隔符.
如果条目不存在, 创建一个新用户变量 Path ，然后将 flutter\bin的全路径作为它的值.
在“用户变量”下检查是否有名为”PUB_HOSTED_URL”和”FLUTTER_STORAGE_BASE_URL”的条目，如果没有，也添加它们。

4. 安装依赖
运行 flutter doctor  检测需要的安装项

5. 检测设备连接
flutter devices

6. Flutter开发工具IDEA开发环境搭建
安装flutter和dart插件，插件的安装安装下图操作：
file->setting->Browse repositories
或者选择install plugin from disk 本地安装

7. Flutter的android开发的环境搭建
a. 安装android sdk
b. idea里面配置jdk和android sdk
需要配置JDK和Android SDK

## 参考网站
1. Flutter百度百科： https://baike.baidu.com/item/Flutter/22498985
2. Flutter中文学习网址: https://flutterchina.club
3. React Native 中文学习网： https://reactnative.cn/docs/0.20/getting-started.html
4. 几款移动跨平台App开发框架比较： https://wiki.lhqmm.com/my/?wid=74b1c7589c684cf3abbbe86197f5e5fb
5. React Native百度百科：https://baike.baidu.com/item/react%20native/20307162?fr=aladdin
5. Dart百度百科：https://baike.baidu.com/item/dart%E8%AF%AD%E8%A8%80/4117161?fr=aladdin
6. Dart学习社区： http://www.cndartlang.com/

### Android studio下载地址
https://developer.android.google.cn/
原来的android开发者社区https://developer.android.google.com 已经不能访问了。
