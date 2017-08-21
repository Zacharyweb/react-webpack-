# react + webpack项目脚手架

##　写在前面
最近在学习react框架，就尝试着自己搭建一个react+webpack项目脚手架，以后可以方便在项目里使用。脚手架里包括`redux`、`react-router`并用`fetch`进行前后端数据交互。下面对这个脚手架的目录结构做一下阐述。

## 项目目录结构
- `/app`——项目主目录
```
├─actions       // 存放actionCreator
├─components    // 存放react木偶组件
├─constants     // 存放redux const 常量的定义
├─containers    // 存放页面组件（智能组件）
│  ├─Page1
│  ├─Page2
│  ├─Home
│  │  └─subpage // 每个页面组件也可以有子页面
│  ├─Page3
│  └─Page4 
├─fetch         // 存放前后端数据交互的方法及接口
├─reducers      // 存放redux规则
├─router        // 存放路由配置文件
├─static        // 存放静态资源
├─store         // 配置redux-store
└─util          // 存放全局工具函数
```

- `index.jsx`——入口文件
- `index.tmpl.html`——模板页面
- `/mock`——模拟后台进行数据交互

## 项目运行

``` bash
# install dependencies
npm install

# open simuate serve 
npm run mock

# serve with hot reload at localhost:8080
npm run start

# build for production with minification
npm run build

```
