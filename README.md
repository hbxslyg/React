# React
[下载React开发环境包 :bookmark_tabs: ](https://github.com/hbxslyg/React/blob/master/React%E7%8E%AF%E5%A2%83.zip?raw=true)

#### 注意
此环境需要有nodeJS环境支持

#### 使用方法
 1. 下载开发环境包
 2. 解压到项目文件件项目文件夹
 3. 打开CMD命令提示符并切换解压后的文件夹
 4. 执行`npm install`命令等待配置环境依赖
```CMD
npm install
```
 5. 执行`npm run dev`命令浏览器实时监控项目
```CMD
npm run dev
```

package.json
```javascript
{
  "name": "react_05",
  "version": "1.0.0",
  "description": "",
  "main": "./src/index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "webpack --mode development",
    "build": "webpack --mode production",
    "start": "webpack-dev-server --mode development"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "classnames": "^2.2.5",
    "prop-types": "^15.6.1",
    "react": "^16.2.0",
    "react-dom": "^16.2.0",
    "react-redux": "^5.0.7",
    "redux": "^3.7.2"
  },
  "devDependencies": {
    "babel-core": "^6.26.0",
    "babel-loader": "^7.1.3",
    "babel-plugin-transform-object-rest-spread": "^6.26.0",
    "babel-preset-env": "^1.6.1",
    "babel-preset-react": "^6.24.1",
    "clean-webpack-plugin": "^0.1.18",
    "css-loader": "^0.28.10",
    "file-loader": "^1.1.11",
    "html-webpack-plugin": "^3.0.4",
    "less": "^3.0.1",
    "less-loader": "^4.0.6",
    "node-sass": "^4.7.2",
    "redux-logger": "^3.0.6",
    "sass-loader": "^6.0.7",
    "style-loader": "^0.20.2",
    "url-loader": "^1.0.1",
    "webpack": "^4.1.1",
    "webpack-cli": "^2.0.10",
    "webpack-dev-server": "^3.1.0"
  }
}

```
