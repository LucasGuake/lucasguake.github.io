# git教程


这篇文章提供了可以在 Hugo 的文章中使用的基本 Markdown 语法示例。

<!--more-->
## 1 部署
### 1. 生成静态页面
baseURL = "https://lucasguake.github.io/ "
```copy
hugo    ##生成静态页面文件
```
### 2. git上传
```copy
cd public
git init    ##初始化仓库
git remote add origin https://github.com/lucasguake/lucasguake.github.io.git    ##链接远程仓库
git add .
git commit -m "first commit"
git push -u origin master
```
## 2 更新
```copy
hugo
cd public
git add .
git status
git commit -m "add blog post"
git push -u origin master
```
{{< admonition >}}
提示以下，commit -m 后面的东西是此次提交的备注，通常用来说明提交人的名字
{{< /admonition >}}





