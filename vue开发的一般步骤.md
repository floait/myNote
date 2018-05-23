# vue开发的一般步骤

------

## 环境搭建
> * 安装node.js和npm

可以去nodejs官方网站下载对应的安装包，默认集成了npm环境,下载地址: [https://nodejs.org/en/download/][1]
这里以解压版为例:
1.下载完成后，在本地的E盘创建目录:node,将下载的zip安装包解压到node文件夹下。
2.打开命令行工具（cmd），依次输入 
```C
e:
cd node/解压的目录名
node -v
npm -v
```
如果打印出了nodejs的版本号,说明已经可以使用了,但是现在这个环境是局部的,只能在当前目录下使用,接下来需要配置用户的环境变量path:
右键我的电脑 => 高级系统设置 => 环境变量
在上方的用户变量下面,点击新建,变量名为path(如果有直接更改即可),将刚才运行`node -v`和`npm -v`成功的目录(其实是`node.exe`和`npm.cmd`所在目录)添加到系统的环境变量里面。
保存退出。重启命令行，分别运行`node -v` 和 `npm -v`,如果打印出版本号,说明已经配置成功。

> * 安装官方脚手架 vue-cli 
```
安装方法: npm install vue-cli
全局安装: npm install -g vue-cli
```
## 依赖安装
这里用到什么安装什么,官方脚手架已经具备了开发环境的webpack部分,以及vue开发所必须的一些组件. 
常用的需要安装的有: 
```vue
vue
vue-router
vue-resource
...
```
## 选择框架

根据项目需要,了解完需求之后,选择合适的开发框架,可以达到事半功倍的效果,节省大量的时间.
常用框架有: 
#### [vuex][2]
#### [iview][3]
#### [vux][4]
#### [官方推荐库][5]


## [end]


  [1]: https://nodejs.org/en/download/
  [2]: https://vuex.vuejs.org/
  [3]: https://www.iviewui.com/
  [4]: https://vux.li/
  [5]: https://curated.vuejs.org/
