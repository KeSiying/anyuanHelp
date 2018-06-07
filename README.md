# 帮助文档 
# 使用建议
GitBook 是一个基于 Node.js 的命令行工具，可使用 Github/Git 和 Markdown 来制作精美的电子书，GitBook 并非关于 Git 的教程。

需要了解git与markdown语法
# gitbook使用
1. 安装nodeJs 
2. 安装gitbook,cnpm install gitbook -g或者npm install gitbook -g

## gitbook常用指令
1. gitbook init 根据sumamry.md中的内容生成chapter内容
2. gitbook install 根据book.json中的配置下载插件
3. gitbook serve 将生成http服务 将生成的网页放到本地端口运行
4. gitbook build 将gitbook进行打包生成html文件

## 常见的目录结构
1. readme.md 相当于首页
2. section.md 相当于首页的分页
3. book.json gitbook使用的插件