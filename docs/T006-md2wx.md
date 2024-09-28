---
title: T006《微信Markdown编辑器》转化Markdown到给微信特制的HTML
---
直达链接: [https://doocs.github.io/md/](https://doocs.github.io/md/)
备用链接: [https://doocs.gitee.io/md/](https://doocs.gitee.io/md/)

Markdown语法简洁, 格式通用, **微信Markdown编辑器**可以将Markdown即时渲染为微信图文，让你不再为微信文章排版而发愁！只要你会基本的 Markdown 语法，就能做出一篇样式简洁而又美观大方的微信图文。


## 最简单的使用方法

![](https://www.v2fy.com/asset/0i/OnlineToolsBook/OnlineToolsBookMD/T006-md2wx.assets/73590429-3c85ef00-451d-11ea-8c12-33f09e0eac45.gif)
[上图gif超清图地址](https://user-images.githubusercontent.com/15868458/73590428-3bed5880-451d-11ea-85af-89afd6c88ee6.gif)



## 自定义css

为图片描边并添加金色阴影效果

```
image {
  background:#000;
  border:1px solid #fff;
  border-width:5px 5px 5px 5px;
  box-shadow:1px 1px 5px #F0BB40;
  -webkit-box-shadow:1px 1px 5px #F0BB40;
  -moz-box-shadow:1px 1px 5px #F0BB40;
  width:100%
}
```

![](https://www.v2fy.com/asset/0i/OnlineToolsBook/OnlineToolsBookMD/T006-md2wx.assets/73591152-fda86700-4525-11ea-95e0-9bae1a7bb629.gif)


## 为文章更换主色调

微信Markdown编辑器预制了**经典蓝**,**翡翠绿**,**活力橘**三种颜色

![](https://www.v2fy.com/asset/0i/OnlineToolsBook/OnlineToolsBookMD/T006-md2wx.assets/73591290-cf2b8b80-4527-11ea-92d0-715ae5af7158.gif)
[上图gif超清图地址](https://user-images.githubusercontent.com/15868458/73591291-cf2b8b80-4527-11ea-9624-1e46c5d2389d.gif)

更换主色调的信息会被记录到本地浏览器,下次打开页面, 依然显示我们自定义的色调

![](https://www.v2fy.com/asset/0i/OnlineToolsBook/OnlineToolsBookMD/T006-md2wx.assets/73591382-fe8ec800-4528-11ea-8517-99909cbce844.png)


## 主界面的可选项

![](https://www.v2fy.com/asset/0i/OnlineToolsBook/OnlineToolsBookMD/T006-md2wx.assets/73591677-80ccbb80-452c-11ea-93a5-2e5383421e61.png)

## 如何解决微信编辑器无法转存海外图片?

如果markdown中含有图片外链, 并且图片外链的图床在海外, 比如Github,markdown被转换为微信格式,粘贴到微信编辑器时, 微信编辑器无法将图片转存到微信服务器, 这就要求我们手动重传所有图片

解决方法也很简单, 先将markdown粘贴到CSDN的在线markdown编辑器,CSDN的在线编辑器会将图片转存到CSDN(zhaoolee亲测,简书,掘金都不好使,只有CSDN能转存github的图片), markdown中的图片地址也会自动替换到国内, 转换完成后,再将转换完成的markdown粘贴到**微信Markdown编辑器**, 就可以避免微信编辑器无法转存图片了

## 本在线工具直达链接:

[https://doocs.github.io/md/](https://doocs.github.io/md/)



## 小结:

**微信Markdown编辑器**是一个非常好用的工具, 它本身是基于另一个开源项目[微信公众号排版编辑器](https://github.com/lyricat/wechat-format)创建,[微信公众号排版编辑器](https://github.com/lyricat/wechat-format)的界面略显简陋, **微信Markdown编辑器**更加美观, 从功能上二者并无太大区别, 在一个好的工具之上, 开发出更好的工具, 让更好的工具造福人类,这或许就是开源的魅力吧~



