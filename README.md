# Welcome to Jekyll!
#
# This config file is meant for settings that affect your whole blog, values
# which you are expected to set up once and rarely need to edit after that.
# For technical reasons, this file is *NOT* reloaded automatically when you use
# 'jekyll serve'. If you change this file, please restart the server process.

# Site settings
title: 徐代龙的技术专栏
brief-intro: Android and Python Coder
baseurl: "" # the subpath of your site, e.g. /blog
url: "https://643435675.github.io" # the base hostname & protocol for your site

permalink: /:year/:month/:day/:title/

# other links
twitter_username: #gaohaoyang126
facebook_username: #gaohaoyang.water
github_username:  643435675
email: 643435675@QQ.com
weibo_username: 3115521wh
zhihu_username: hll643435675
linkedIn_username: gaohaoyang
dribbble_username:

description_footer: 来自徐代龙的个人专栏！

# comments
# two ways to comment, only choose one, and use your own short name
# 两种评论插件，选一个就好了，使用自己的 short_name
duoshuo_shortname: #hygblog
disqus_shortname: #gaohaoyang

# statistic analysis 统计代码
# 百度统计 id，将统计代码替换为自己的百度统计id，即
# hm.src = "//hm.baidu.com/hm.js?xxxxxxxxxxxx";
# xxxxx字符串
baidu_tongji_id: 1cc1fc4b4b456bf7c99ce80aec5bf009
google_analytics_id: UA-72449510-4 # google 分析追踪id

# Build settings
markdown: kramdown

kramdown:
  input: GFM
  syntax_highlighter: rouge

# port
# port: 1234

# url
category_dir: category/
tag_dir: tag/

# excerpt
excerpt_separator: "\n\n\n\n"

# paginate
plugins: [jekyll-paginate]
paginate: 6
port: 4001
