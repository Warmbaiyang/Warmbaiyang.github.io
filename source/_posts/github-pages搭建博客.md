---
title: github + pages搭建博客
date: 2020-08-23 16:17:39
tags: 分享一个自己搭建的博客 github + pages
page:
---

GitHub Pages 本用于介绍托管在 GitHub 的项目， 不过，由于他的空间免费稳定，用来做搭建一个博客再好不过了。

缺点：只能放静态页面，也就说github pages只能解析html、css、js，无法解析后端语言。

**[用户名.github.io] 将来访问路径**

博客搭建步骤：

## 1. 下载安装git

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823152611289.png#pic_center)
1.1 安装好后鼠标右键左面出现 git 说明已经安装完成
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020082315295890.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)
1.2 查看安装 版本和配置完成 打开命令窗口 cmd  输入git -v 或者 git
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823153412855.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

## 2. hexo创建博客
1. 安装步骤
在桌面新创建一个文件夹 命名为 blog
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823153721344.png#pic_center)
1.1 进入blog文件夹 鼠标右键 选 git Bash here
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823153832636.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)
1.2  安装

```javascript
 npm config set registry https://registry.npm.taobao.org --global
 npm config set disturl https://npm.taobao.org/dist --global
```
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020082315405420.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

## 3. 安装hexo
输入 **npm install -g hexo** 下方为安装完成
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154226163.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)
**hexo -v   查看hexo的版本信息**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154332915.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

## 4. 初始化博客
hexo init   **初始化**   完成
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154514972.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

## 5. 生成静态页面
hexo generate    **生成静态页面**    完成
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154633762.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

## 6. 打开 blog文件 
可以看到 成功生成网页
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154719557.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

## 7. 启动服务
hexo server 启动
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154913621.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)

访问站点
**http://localhost:4000/   通过这个地址就可以访问了**  ==已完成==
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823155030651.png#pic_center)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200823154947554.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTk3NDY4Nw==,size_16,color_FFFFFF,t_70#pic_center)
