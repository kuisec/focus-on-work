---
# 草案开关，草案开启将不会转换此文章，true或者false，写完文章务必将其修改为false
draft: true

# 标题
title: "{{ replace .TranslationBaseName "-" " " | title }}"

# 文章链接字段
slug: "{{ .BaseFileName }}"

# 副标题
subtitle: ""

# 标签，用“|”隔开
stack: ""

# 外站链接，留空不显示
website_link: ""

# github 项目地址，留空不显示
github_link: ""

# 封面颜色，例如 #437aac
color: "transparent"

# 文章索引，索引值越小，优先级越高
index: 1

# 封面图片，背景透明，1000x563，比例16:9
thumb_image: ""

# 内容图片，背景透明，500x445，比例4:3
cover_image: ""
---

