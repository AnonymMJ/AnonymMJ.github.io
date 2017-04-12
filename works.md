---
layout: page
title: "works"
description: "知之真切笃实处即是行，行之明觉精察处即是知 "
header-img: "img/semantic.jpg"
---

{% for talk in site.talks %}
<div class="post-preview">
        <div class="post-content-preview">
            {{ talk.content }}
        </div>
    <p class="post-meta">Talked on {{ talk.date | date: "%Y-%m-%d %m:%s" }}</p>
</div>

<hr>
{% endfor %}







