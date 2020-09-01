# test

![https://img.shields.io/badge/taro-%5E1.3.20-brightgreen](https://img.shields.io/badge/taro-%5E1.3.20-brightgreen)
![https://img.shields.io/badge/MobX-%5E4.8.0-brightgreen](https://img.shields.io/badge/MobX-%5E4.8.0-brightgreen)

## 一、使用

> 说明：本项目只支持 H5 和微信小程序的项目开发

### 1. 安装依赖

```bash
$ npm install # 或 yarn install
```

### 2. 本地开发

```bash
$ npm run dev:h5 # h5 项目 访问：http://localhost:10086/lite/album
$ npm run dev:weapp # 微信小程序项目
# TODO: 现在填写的 APPID 是个人的小程序，等产品申请下来之后再替换
```


## 目录结构

```
|- config                 // 项目编译配置文件
|- src                    // 项目源码
| |- assets               // 图片资源
| |- components           // 组件
| |- pages                // 页面
| |- store                // 统一数据状态
| |- styles               // 样式
| |- utils                // 常用库
| |- app.js               // 项目入口文件
| |- app.scss
| |- index.html           // h5 页面模块文件
| |- router.js            // h5 页面自定义路由设置文件【更改入口文件页面路由时，不要忘了这个文件】
|- project.config.js
|- README.md
```

## 相关资料

1. [Taro 文档](https://nervjs.github.io/taro/docs/README.html)
2. [MobX 文档](https://cn.mobx.js.org/)
3. [微信小程序文档](https://developers.weixin.qq.com/miniprogram/dev/framework/)
4. [微信小程序 - 腾讯视频插件使用文档](https://mp.weixin.qq.com/wxopen/plugindevdoc?appid=wxa75efa648b60994b&token=1327615254&lang=zh_CN&scene=21&uin=&key=&devicetype=Windows+7&version=6206034d&ascene=1&winzoom=1#-)
5. [h5 - 腾讯视频 JSSDK 使用文档](https://m.v.qq.com/txp/v3/)