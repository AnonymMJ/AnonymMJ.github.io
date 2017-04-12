---
layout: page
title: "works"
description: "知之真切笃实处即是行，行之明觉精察处即是知 "
header-img: "img/semantic.jpg"
---

{% for talk in paginator.talks %}
<div class="post-preview">
        <div class="post-content-preview">
            {{ post.content | strip_html | truncate:55 }}
        </div>
    <p class="post-meta">Talked on {{ post.date | date: "%Y-%m-%d" }}</p>
</div>

<hr>
{% endfor %}







