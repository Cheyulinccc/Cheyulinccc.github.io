实验一 在Github上用Markdown创建技术博客
一、实验目的
1.熟悉Github网站
2.掌握Markdown语法
二、实验任务
1.注册Github账号
2.创建Gihub Pages repository
3.发布第一篇博客
4.学习Markdown
5.利用Hexo生成博客并部署到Github
三、实验步骤与结果
1.本地配置Hexo
①安装git
②安装node
③设置npm镜像为淘宝
 npm config set registry http://registry.npm.taobao.org
④安装hexo
 nmp install -g hexo-cli
⑤初始化站点
 hexo init myhexo
 cd myhexo
 npm install
⑥浏览本地站点
 hexo server

2.在Github上部署hexo
 ①在GitHub上新建respository,名称是用户名githu.io
 ②修改配置文件_config.ym的deploy部分，注意空格

3.部署到Github Page
 ①开通Github账号
 ②创建一个respository，名称必须是——用户名.github.io
 ③修改配置文件——-config.yml
 

4.新建博客


四、实验小结
通过这次的学习，让我们初次接触到了博客，学会了如何利用Hexo搭建自己的博客系统，并且熟悉了Github网站。还学习了MakeDown编辑器，利用MakeDown编写文本。
