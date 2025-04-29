
---
title: '{{ replace .File.ContentBaseName "-" " " | title }}' # 当前文章标题
description: ''  # 当前文章副标题
date: '{{ .Date }}' # 创建日期
author: "Rickey" # 作者
slug: '' # 文章Url
url: '' # 文章Url
showToc: true # 显示目录
TocOpen: true # 自动展开目录
enableCopyright: true # 显示版权信息
comments: true # 显示评论
weight: null # 若置顶则为对应数字
draft: false # 是否为草稿
# 分类
Categories:
 - Example
  
# 标签
Tags:
 - Example

# 关键字
keywords:
 - keywords1
 - keywords2
 - keywords3

cover:
  # 图片的替代文本，用于无障碍访问和在图片无法加载时显示的文本
  alt: ''
  # 图片的说明文字，通常用于描述图片内容 
  caption: '' 
  # 封面图片的路径，可以是相对路径或绝对 URL，用于指定实际的封面图像
  image: '' 
  # 指示 image 路径是否为相对路径。如果为 true，则认为路径是相对于当前内容文件的；如果为 false，则认为是绝对路径
  relative: false 
---
