﻿Fly Template 由layui官方社区（Fly社区）友情抽取，页面基于 layui 搭建而成，提供了全屏和固宽两类排版，并且具备响应式适配能力，可很好地作为简约型问答社区的页面支撑。

# 目录说明  
```
├─html 可直接预览的模版文件
│  ├─jie
│  ├─public
│  └─user
├─res 静态资源
│  ├─css
│  ├─images
│  │  ├─avatar
│  │  └─other
│  ├─layui
│  └─mods 模版业务模块
└─views 动态模版参考（NodeJS端）
    ├─jie
    ├─public
    └─user
```

# 全屏风格
模版提供了全屏风格，你可以打开 html/full.html预览效果
使用全屏风格只需在原有css的基础上，引入 css/full.css即可。

# 字符解析
该模版自带一个特定语法的编辑器，当你把内容存储到数据库后，在页面读取后浏览，会发现诸如“表情、代码、图片”等无法解析，这是因为需要对该内容进行一次转义，通常来说这是在服务端完成的，但鉴于简单化，你还可以直接在前端去解析，在模版的detail.html中，我们已经把相关的代码写好了，你只要打开注释即可。

当然，如果觉得编辑器无法满足你的需求，你也可以把该编辑器换成别的HTML编辑器。

# 在线预览
http://fly.layui.com/

# 开源协议
MIT License

# 社区相关
* [Fly社区](http://fly.layui.com/)
* [码云](http://git.oschina.net/sentsin/fly)
* [GitHub](https://github.com/layui/fly)
