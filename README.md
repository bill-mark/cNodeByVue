# cNodeByVue

写这篇日志的时候，当时正在开发一个内网WEB管理项目，比较了VUE和ng2半天还是决定先用VUE来解放生产力。
等ng2正式版出来且坑被填差不多再上，哈哈。
这个项目主要是来为正式项目使用VUE赞赞经验，借鉴了react社区的react实现cNode网站的思路，感谢cNode网站开放的API。


├─index.shtml          渲染列表页面
├─content.shtml        渲染详情页面
├─url.shtml            测试url 方法页面
├─inc                  碎片文件
│   ├─bar.html             侧边栏代码
│   ├─footer.html          版权部分代码
│   ├─head.html            head区域调用js等代码
│   └─header.html          页头logo以及导航代码
└─res                  资源文件
    ├─image
    ├─js
    │  ├─common             我的代码目录
    │  │  ├─common.js           公共执行js
    │  │  └─method.js           自定义方法js
    │  ├─jquery             jquery源码目录
    │  ├─plugins            其他插件目录
    │  │  └─laypage             laypage 分页插件
    │  └─vue                VUE源码目录
    └─style
        ├─style.scss        sass源文件
        ├─style.css         编译好的css 文件
        ├─base
        └─scss
