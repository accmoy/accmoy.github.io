# 部署静态网站



## Linux安装hugo
- sudo apt-get install hugo

## 创建一个文件夹来存放hugo网站
- cd Downloads
- mkdir mysite
- hugo new site mysite
* 创建后目录如下
<img src="/7.jpeg">

## 在hugo选择一个主题网站
- cd mysite
- git clone http://github.com/dillonzq/LoveIt.git 
<img src="/8.jpeg">

<img src="/9.jpeg">

## 在config.toml进行基础配置
<img src="/10.jpeg">

## 在content/post/文件夹里面去创建文章
<img src="/11.jpeg">

<img src="/12.jpeg">

## 运行hugo查看网站
- hugo serve --buildDrafts
<img src="/14.jpeg">

<img src="/13.jpeg">

## 将网站部署到github上
- hugo --theme=LoveIt --baseUrl="https://accmoy.github.io/" --buildDrafts
<img src="/15.jpeg">

- cd public
- git init
<img src="/16.jpeg">

- git add .
- git commit -m "first_push"
<img src="/17.jpeg">

- git remote add origin https://github.com/accmoy/accmoy.github.io.git
- git push -u origin master
<img src="/18.jpeg">
***
#### 学习资料:<https://www.bilibili.com/video/BV1x64y117PX/?spm_id_from=333.337.search-card.all.click&vd_source=b4ae45c6eb91609486227ca4c1c93971>

