# olivercm.github.io
#### 修改配置文件  
quickstart/config.toml

#### 本地测试  
quickstart目录下执行：  
hugo server -D

#### 发布文章步骤
1、quickstart目录下执行：  
hugo new post/my-first-post.md

2、修改content下创建的md文件中的draft为false，编辑文章，增加tags、categories   
命令行： treer -d 文件夹  
可以打印出目录结构  

3、回到quickstart目录执行：  
hugo

4、推送修改到github

参考：  
1、https://gohugo.io/getting-started/quick-start/  
2、https://github.com/olOwOlo/hugo-theme-even/blob/master/README-zh.md#installation  
3、https://mogeko.me/2018/018/  
