---
layout: page
title: 关于
description: 关于
keywords: About，关于
comments: true
menu: 关于
permalink: /about/
---
## 联系




<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/qrcode.jpg" alt="闷骚的程序员" />
</li>
{% endif %}
</ul>
# APP

hi，这是我用百度网盘分享的内容~复制这段内容打开「百度网盘」APP即可获取 
链接:https://pan.baidu.com/s/1djcfYUiMBjQK-se_cgHhNA 
提取码:1111
