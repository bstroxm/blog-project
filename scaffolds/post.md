---
title: {{ title }}
date: {{ date }}
tags: # 文章标签，一篇文章可以多个标签
categories: # 文章分类，只建议一篇文章一个分类
keywords: # 文章关键字，SEO 时需要，默认文章标题
img: # 文章特征图
top: false # 文章是否置顶
hide: false # 文章是否在首页隐藏
cover: false # 文章是否需要加入到首页轮播封面中
coverImg: # 文章在首页轮播封面需要显示的图片路径，如果没有，则默认使用文章的特色图片
password: # 文章阅读密码，如果要对文章设置阅读验证密码的话，就可以设置 password 的值，该值必须是用 SHA256 加密后的密码，防止被他人识破。前提是在主题的 config.yml 中激活了 verifyPassword 选项
toc: true # 文章是否开启toc
mathjax: false # 文章是否开启数学公式支持（需要在主题的 _config.yml 文件中也需要开启才行）
summary: # 文章摘要，自定义的文章摘要内容，如果这个属性有值，文章卡片摘要就显示这段文字，否则程序会自动截取文章的部分内容作为摘要
reprintPolicy: # 文章转载规则
---
