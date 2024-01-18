## 开发

```bash
# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npmmirror.com

# 启动服务
npm run dev


# 后端IP配置
在.env.*文件中配置http:// 或 https:// 后面部分
vue.config.js 中 默认http:// 如要修改在此文件中修改
```

浏览器访问 http://localhost:80

## 发布

```bash
# 构建测试环境
npm run build:dev

# 构建生产环境
npm run build:prod

# 本地启动使用测试环境配置
npm run dev

# 本地启动使用正式环境配置
npm run prod
```

## 目录结构
```
|-- WRKJ-UI
    |-- .editorconfig
    |-- .env.development
    |-- .env.pro-env
    |-- .env.production
    |-- .env.staging
    |-- .eslintignore
    |-- .eslintrc.js
    |-- .gitignore
    |-- babel.config.js
    |-- directoryList.md
    |-- package-lock.json
    |-- package.json
    |-- README.md
    |-- vue.config.js
    |-- bin
    |-- build
    |-- public
    |   |-- favicon.ico
    |   |-- flying.png
    |   |-- index.html
    |   |-- robots.txt
    |   |-- black
    |   |-- html
    |   |-- white
    |-- src
        |-- App.vue
        |-- iconfont.js
        |-- main.js
        |-- permission.js
        |-- resetMessage.js
        |-- settings.js
        |-- api
        |-- assets
        |-- components
        |-- directive
        |-- i18n
        |-- layout
        |-- plugins
        |-- router
        |-- store
        |-- utils
        |-- views
```
