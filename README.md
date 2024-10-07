# Natours

Natours

## rem 单位

1rem 等于根节点的 font-size

### box-sizing inherit 强制继承

### html font-size: 62.5% 默认 100%为 16px 62.5 为 10px

## 安装 sass

### 1. npm init

### 2. npm install node-sass --save-dev

## --save-dev 的解释

### --save 添加依赖

### --dev 添加开发是使用的依赖

## 编译 sass 文件

### 编写脚本执行命令 在 package.js 中 scripts 中添加 "compile:sass": "node-sass sass/main.scss css/style.css -w"

### 执行 npm run compile:sass

### -w 是检测文件变化 自动编译

## 安装 live-server npm install live-server -g 全局安装

### 执行命令 live-server 即启动一个 localhost 的 server 并默认浏览器打开
