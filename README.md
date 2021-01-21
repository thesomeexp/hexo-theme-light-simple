# hexo-theme-light-simple

This theme is modify by Default theme Light. [Demo here.](https://someexp.com)

## Install

Execute the following command and modify `theme` in `_config.yml` to `hexo-theme-light-simple`.

```
cd themes
git clone https://github.com/thesomeexp/hexo-theme-light-simple.git
```

## Update

Execute the following command to update hexo-theme-light-simple.

```
cd themes/hexo-theme-light-simple
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: 
  Archives: archives
  About: about

widgets:
- tag
- footer

```

- **menu** - Main navigation menu (Remember to create the same file in your ```source/about/index.md```)
- **widget** - Widgets displaying in sidebar

## Use

Default scaffolds/post config:

~~~
---
title: {{ title }}
date: {{ date }}
updated: {{ date }}
tags: 
urlname: 
original: 
---
~~~

- **title** - Title
- **date** - Created date
- **updated** - Updated date
- **tags** - Some tags
- **link** - Point to some page on your websit (when you use this, **urlname** doesn't work)
- **urlname** - Posted article url link 
- **original** - Show ```themes/hexo-theme-light-simple/layout/_partial/post/copyright.ejs``` at the end? true/false

create article

~~~
hexo new 'title'
~~~

# Q&A

## How to use 'Read More' ?

Add 

~~~
<!--more-->
~~~

in your article. 

# hexo-theme-light-简单版

这个主题修改自Hexo默认的Light主题. [示例在这.](https://someexp.com)

## 安装

执行下面的命令和修改hexo配置文件 `_config.yml` 的 `theme` 属性的值为 `hexo-theme-light-simple` .
进入themes文件夹, `hexo-theme-light-simple` 下载主题
```
cd themes
git clone https://github.com/thesomeexp/hexo-theme-light-simple.git
```

## 更新

执行下面的命令来升级hexo-theme-light-简单版

```
cd themes/hexo-theme-light-simple
git pull
```

## 配置

默认配置:

``` yaml
menu:
  Home: 
  Archives: archives
  About: about

widgets:
- tag
- footer

```

- **menu** - 主要的导航栏菜单 (如果创建了, 那么记得去相关的目录创建对应的index.md文件, 比如: ```source/about/index.md```)
- **widget** - 一些是否显示的侧边栏小组件

## 使用

默认的草稿模板 scaffolds/post.md 配置:

~~~
---
title: {{ title }}
date: {{ date }}
updated: {{ date }}
tags: 
urlname: 
original: 
---
~~~

- **title** - 文章标题
- **date** - 文章创建日期
- **updated** - 更新时间
- **tags** - 一些文章相关标签
- **link** - 该链接能指向source的所有.md文章 (当你使用这个配置时, **urlname** 配置不会工作)
- **urlname** - 发布文章的永久链接, 也就是文章的链接
- **original** - 是否在文章末尾显示 ```themes/hexo-theme-light-simple/layout/_partial/post/copyright.ejs``` ? 值为: **true** 或 **false**

创建文章

~~~
hexo new 'title'
~~~

# Q&A

## 如何使用 'Read More' (查看更多) ?

在文章中添加: 

~~~
<!--more-->
~~~

来区分. 
