## wechat-wepy 微信小程序组件化开发框架


	使用wepy-cli脚手架搭建wepy框架

## 项目启动，打开方式
	进入项目根目录，开发实时编译 wepy build --watch
	打开 `微信web开发者工具` ，以dist文件夹打开

## 开发者工具使用


- 	使用微信开发者工具新建项目，本地开发选择dist目录。
- 	微信开发者工具-->项目-->关闭ES6转ES5。重要：漏掉此项会运行报错。
- 	微信开发者工具-->项目-->关闭上传代码时样式自动补全 重要：某些情况下漏掉此项会也会运行报错。
- 	微信开发者工具-->项目-->关闭代码压缩上传 重要：开启后，会导致真机computed, props.sync 等等属性失效。#270
- 	项目根目录运行wepy build --watch，开启实时编译。

## 功能要点

- 	首页启动页面: pages/default
	
-	实现功能：

> 1.   wepy组件Repeat

> 2.   生成list列表

> 3.   自定义组件（使用button，.user: 绑定用户自定义组件事件，通过$emit触发。 使用$broadcast修改子组件参数）

> 4.   slot内嵌套

> 5.   watch监听改变值

##界面

   <image src="/src/images/defaultPage.png"></image>
