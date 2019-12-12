# olivercm.github.io
##### 修改配置文件  
quickstart/config.toml

##### 本地测试  
quickstart目录下执行：  
hugo server -D

##### 发布文章步骤
1、quickstart目录下执行：
hugo new post/my-first-post.md

2、修复创建的md文件中的draft为false，编辑文章

3、回到quickstart目录执行：
hugo

4、命令行发布：  
git add -A  
git commit -m "[介绍，随便写点什么，比如日期]"  
git push -u origin master  
或  
SourceTree

参考：
1、https://gohugo.io/getting-started/quick-start/  
2、https://github.com/olOwOlo/hugo-theme-even/blob/master/README-zh.md#installation  
3、https://mogeko.me/2018/018/  
