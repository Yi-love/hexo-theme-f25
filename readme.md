# hexo-theme-f25
this is a blog theme for hexo.

demo : [https:jinyy.app](https://jinyy.app)

demo : [https:futu.im](https://futu.im)


github: [https://github.com/futuweb/futu.im](https://github.com/futuweb/futu.im)


## npm install

```sh
git clone https://github.com/Yi-love/hexo-theme-f25.git
```

## config 
not next page , only one page.

```yml
# _config.yml
# required

title: 
subtitle:  
description:  
keywords:  
author:  
language: zh-CN
timezone: Asia/Shanghai

copyright:  


# required
menu:
  Home: /
  About: /about

index_generator:
  path: ''
  per_page: 10000

# not next page , only one page.
per_page: 10000

# required
theme: hexo-theme-f25
```

```yml
# themes/hexo-theme-f25/_config.yml
# required

default_cover: images/default_cover.jpg
google_analytics: 
gitalk_clientID: 
gitalk_clientSecret:
gitalk_repo: you_repo
gitalk_owner: you_name
gitalk_admin: you_name,user_one
gitalk_pathname_max_length: 50
favicon: /images/favicon.ico
```


## source/\_posts
source post file.

example:

```md
---
date: 2018-11-20 12:00
title:  this is a title
subtitle: subtitle show you
cover: /images/first_cover.jpg
categories: [Node.js]
---
```

