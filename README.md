webpack 4 ：从0配置到项目搭建


### webpack 4 的零配置主要应用于：

1. entry 默认设置为 ./src/index.js
2. output 默认设置为 ./dist/main.js
3. production 和 development 两种模式

### 项目搭建，我们对webpack的诉求是：

1. js的处理：转换 ES6 代码，解决浏览器兼容问题

``` npm i babel-core babel-loader babel-preset-env --save-dev ```

2. css的处理：编译css，自动添加前缀，抽取css到独立文件
3. html的处理：复制并压缩html文件
4. dist的清理：打包前清理源目录文件
5. assets的处理：静态资源处理
6. server的启用：development 模式下启动服务器并实时刷新

### 感谢 
> https://phoebecodespace.github.io/2018/07/04/webpack-4-tutorial/
  https://segmentfault.com/a/1190000014466696?utm_source=index-hottest/*&^%$#articleHeader5


