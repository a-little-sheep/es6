# es6学习中
###将es6转化为es5 
在局部安装babel-cli
```
npm install --save-dev babel-cli
```
修改package.json
```
"scripts": {
    "build": "babel src -d lib"
  }
```
转码的时候，就执行下面的命令
```
$ npm run build
```
当安装babel-cli 时会将自动安装 babel-node，babel-node命令可以直接运行ES6脚本
```
$ babel-node es6.js
```
