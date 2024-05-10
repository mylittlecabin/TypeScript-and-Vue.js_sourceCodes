## 环境搭建
### 背景
《TypeScript+Vue.js前端开发从入门到精通》读书学习代码

#### 安装node
访问官网
```
https://nodejs.org/en
```

#### 安装TypeScript
安装命令
```
npm install -g typescript
```
检查安装是否成功
```
tsc -v 
```
如果安装成功，可以看到版本号

#### 编译ts文件
```
tsc HelloWorld.ts
```
编译成功，会在同目录下生成同名的js文件

#### 运行js文件
```
node HelloWorld.js
```

#### 安装ts-node
在vscode中调试运行需要
```
npm install -g ts-node@8.5.4
```

