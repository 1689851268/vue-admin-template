# 项目结构

- build/index.js - webpack 配置文件
- mock - mock 数据的文件夹
- public - 放置一些静态资源。项目打包时，webpack 不会编译这个文件夹，该文件夹会被原封不动的打包到 dist 文件夹里面
- src - 存放编写的业务代码
  - api - 存放用于发送请求的代码
