# salt-tool

---

## 简介

在 Salt 的整体解决方案中，使用 [Nowa](http://nowa-webpack.github.io/docs/) 作为工具层面的支持。

Nowa 是基于 webpack 的前端开发解决方案集合。包含一系列前端开发生命周期中可能使用到的工具

## 快速开始

- 安装

```shell
npm i nowa -g && nowa install
```

> 如果提示没权限，请在命令前面加 sudo

- 初始化

```shell
nowa init salt
```

- 启动服务器

```shell
nowa server
```

![](http://nowa-webpack.github.io/docs/screenshot-server-use.png)

- 打开浏览器

访问命令行中提示的地址，就可以看到刚刚创建的项目页面啦！

## 常用功能

- [初始化新项目](http://nowa-webpack.github.io/docs/xin_xiang_mu.html)
- [初始化新页面](http://nowa-webpack.github.io/docs/xin_ye_mian.html)
- [初始化新模块](http://nowa-webpack.github.io/docs/xin_mo_kuai.html)
- [本地开发服务器](http://nowa-webpack.github.io/docs/ben_di_kai_fa.html)
- [通过网络代理进行远程调试](http://nowa-webpack.github.io/docs/yuan_cheng_tiao_shi.html)
- [https 配置](http://nowa-webpack.github.io/docs/https_pei_zhi.html)
- [模块热替换](http://nowa-webpack.github.io/docs/mo_kuai_re_ti_huan.html)
- [覆盖默认的 webpack 配置](http://nowa-webpack.github.io/docs/fu_gai_mo_ren_de_webpack_pei_zhi.html)
- [环境变量注入](http://nowa-webpack.github.io/docs/huan_jing_bian_liang.html)
- [https 配置](http://nowa-webpack.github.io/docs/https_pei_zhi.html)
- [项目构建](http://nowa-webpack.github.io/docs/xiang_mu_gou_jian.html)
- [组件库的定制构建](http://nowa-webpack.github.io/docs/zu_jian_ku_de_ding_zhi_gou_jian.html)

## 目录结构

```
.
├── abc.json  ------------------------- 项目构建配置文件
├── favicon.ico  ---------------------- 页面图标
├── html  ----------------------------- html目录
│   └── index.html  ------------------- 入口页面
├── package.json  --------------------- 项目配置
├── README.md  ------------------------ 说明文件
└── src  ------------------------------ 源码目录
    ├── app  -------------------------- 项目级代码
    │   ├── app.js  ------------------- 项目级脚本逻辑
    │   ├── app.styl  ----------------- 全局样式
    ├── components  ------------------- 业务模块集合目录
    ├── i18n  ------------------------- 国际化文案资源文件
    │   ├── en.js
    │   ├── index.js  ----------------- 国际化资源加载器
    │   └── zh-cn.js
    ├── images  ----------------------- 图片资源目录
    └── pages  ------------------------ 页面集合目录
        └── demo  --------------------- 某一个页面
            ├── index.js  ------------- 页面入口文件
            ├── actions.js  ----------- 事件列表
            ├── store.js  ------------- 存储器
            ├── PageDemo.js  ---------- 页面视图逻辑
            └── PageDemo.styl  -------- 页面样式
```

## 链接

- [提问和反馈](https://github.com/nowa-webpack/nowa/issues/new)
- [常见问题](http://nowa-webpack.github.io/docs/chang_jian_wen_ti.html)
- 更多信息请访问[文档站点](http://nowa-webpack.github.io/docs/)
