# hoo-bridge-framework
Hank's OO bridge framework

#### 项目简介

    该项目始于2014年，期间多个产品和项目磨合改进，用于：ios/android/mobile/web 跨平台桥接的一款轻量级框架。
    2016年小程序发布以来，结合当前移动端平台已完成：hoo.bridge.android.js、hoo.bridge.wkwebview.js、hoo.bridge.uiwebview.js（IOS平台两种）、hoo.bridge.web.js、hoo.bridge.xcx.js等几个平台的常用桥接功能的实现。
    其中，android和ios平台需要对应原生实现，web端做了兼容处理，小程序端已做了微信小程序接口封装实现，支付宝小程序目前计划中。

#### 核心思路
    
    基于面向对象的思维，实现了JS的继承体系。
    桥接框架实现思路是面向接口编程，即定义需实现的桥接接口，根据平台采用对应的平台实现。
