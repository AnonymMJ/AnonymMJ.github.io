---
layout: page
title: "Talks"
description: "你看到的，是我的所有文字说说"
header-img: "img/semantic.jpg"
---

{% for talk in site.posts %}
{% if talk.istalk %}
<div class="post-preview">
        <div class="post-content-preview talk-container">
            {{ talk.content }}
        </div>
    <p class="post-meta">Talked on {{ talk.date | date: "%Y-%m-%d %H:%M" }}</p>
</div>
<hr>
{% endif %}

{% endfor %}







