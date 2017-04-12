---
layout: page
title: "works"
description: "知之真切笃实处即是行，行之明觉精察处即是知 "
header-img: "img/semantic.jpg"
---


<center>
    <p><img src="http://7xlfkx.com1.z0.glb.clouddn.com/white2.jpg" align="center"></p>
</center>


{% for talk in paginator.talks %}
<div class="post-preview">
        <div class="post-content-preview">
            {{ post.content | strip_html | truncate:55 }}
        </div>
    <p class="post-meta">Talked on {{ post.date | date: "%Y-%m-%d" }}</p>
</div>

<hr>
{% endfor %}







