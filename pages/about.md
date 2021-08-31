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

# 目前收录***120本***

![Alt](https://i.loli.net/2021/08/31/UYwyQ9bFjK2q1OW.jpg)
