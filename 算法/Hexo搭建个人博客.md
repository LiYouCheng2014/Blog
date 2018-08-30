---
title: Hexo搭建个人博客
date: 2018-08-30 11:51:50
categories: 工具
tags: 
- github
- hexo
---



### 安装hexo

##### 需要先安装Node.js和Git

##### 通过nvm安装Node.js

```
$ curl https://raw.github.com/creationix/nvm/master/install.sh | sh
```

```
$ nvm install stable
```



##### 通过brew安装Git

```
$ brew install git
```



#### 通过npm安装hexo

```
$ npm install -g hexo-cli
```



### 建站Hexo

```
$ hexo init <文件名>
$ cd <文件名>
$ npm install
```

```
.
_config.yml 配置信息
package.json
scaffolds  模板
source 资源文件
	_draft 草稿
	_posts 发布
themes 主题
```



### 使用说明

#### 启动服务

```
$ hexo s
```



#### 创建文章方式

#### 新建文章

```
$ hexo new "文章名"
```



#### 创建草稿

```
$ hexo new draft "文章名"
```



#### 发布草稿

```
$ hexo publish "文章名"
```



#### 发布文章

##### 清除缓存和静态页面

``` 
$ hexo clean
```



##### 生成静态页面

```
hexo generate 简写:hexo g
```



##### 配置

```
$ hexo deploy 简写:hexo d
```





[部署](http://gonghonglou.com/2016/02/03/firstblog/)

[hexo官方文档](https://hexo.io/zh-cn/docs/index.html)

[创建标签和分类](https://www.jianshu.com/p/e17711e44e00)









