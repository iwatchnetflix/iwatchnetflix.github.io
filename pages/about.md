---
layout: page
title: About
description: 电影改变生活
keywords: Netflix, 电影，Netflix推荐
comments: false
menu: 关于
permalink: /about/
---

这里是，爱看网飞。

电影「人生的另一种可能」。

相信一部好的影片，可以改变生活轨迹。

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/qrcode.jpg" alt="爱看网飞" />
</li>
{% endif %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
# <div class="btn-inline">
# {% for keyword in skill.keywords %}
# <button class="btn btn-outline" type="button">{{ keyword }}</button>
# {% endfor %}
#</div>
# {% endfor %}
