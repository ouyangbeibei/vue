# Webpack install
运作步骤：
1.npm init
2.安装
3.添加文件
4.改文件
5.安装插件
6.打包
7.浏览器预览


1-$ npm init

2-$ npm i -g webpack 

或直接接安装指定版本：npm install --save-dev webpack@3.10.0

3-4.src/index.js   dist/index.html

5-$ npm install --save lodash

$ npm i babel-loader babel-core babel-preset-es2015 babel-preset-react
webpack

6-本地： ./node_modules/.bin/webpack 入口路径 打包路径
全局：webpack 入口路径 打包路径

7-预览
mac：open dist/index.html
win：start dist/index.html


简书文章：https://www.jianshu.com/p/10d8086acf0b