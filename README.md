# ifaas-sdc-web
## 1、项目结构

```bash
  ├── dist                        # 项目打包文件
  ├── app                           # Electron本地打包文件
  ├── public                        # 静态资源
  ├── src							# 开发的主体位置
  │     ├── components              # 通用组件
  │     ├── config                  # 统一配置请求地址
  │     ├── container               # app子模块，一个模块对应一个文件夹
  │     ├── router                  # 路由界面
  │     ├── utils                   # 工具类
```

一般来说我们的开发都在 src/ 下进行，components 中放置项目通用组件， containers 中放置不属于某子模块的页面。对于业务开发，一般在 app/components 的某个模块下进行开发，模块的项目组织如下所示：

## 2、技术选型

vite工具
UI库: Zarm框架 https://gitee.com/zarm/zarm/



其它引用库
| 库名                | 版本    | 说明                               |
| ------------------- | ------- | ---------------------------------- |
| react-zoom-pan-pinch|         | 图片放大缩小                        |

## Getting Started

Install dependencies,

```bash
$ yarn
```
```bash
$ yarn start
```

## Electron本地离线化工具打包流程
   打包工具:electron-builder

```安装打包所需依赖
   进入app文件夹下   yarn install

```打包流程  
    ```项目文件夹    npm run build --pro="electron"

    ```进入app文件夹下  npm run elebuild

## 工具端快捷键
ctrl+shift+i  快捷打开调试功能
