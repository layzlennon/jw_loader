# jw_loader
基于 quick-cocos2d-x 3.3 lua 的热更新小项目, 无需对引擎进行改造， 小巧简洁，无需强后台支持，支持按渠道开放更新，android与ios真机测试通过！

# 运行条件
quick-cocos2d-x 3.3 版本（3.6社区版未测试，理论上也可以）的android或IOS真机

# 主要特性
单个ZIP包，不依赖quick本身的framework，不与项目本身代码混合
这个升级模块本身也可以被更新
支持按渠道来开放更新
支持指定渠道的更新跳转
支持环境ID的判断，以避免误更新
弱后台需求，很多热更新方案中都需要比较强的后端接口配合，此方案
只需要将静态文件上传至WEB服务器即可，不需要动态语言后台的支持，
当然你也可以根据自己的需求去改造。

# 关联项目
TODO: 上传关联的示例项目，以及python的资源打包脚本
