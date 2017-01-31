---
layout: page
title: Drafts
description: 草稿
keywords: 草稿
comments: false
menu: 草稿
permalink: /drafts/
---

<ul class="listing">
{% for draft in site.drafts %}
{% if draft.title != "Draft Template" %}
<li class="listing-item"><a href="{{ draft.url }}">{{ draft.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
