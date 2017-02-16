---
layout: page
permalink: /all-news/
title: All News
---

<ul class="post-list">
    {% for post in site.posts %}
        <li class="post-item">
            <h3 class="post-item__title">
                <a class="post-item__link" href="{{ post.url | prepend: site.baseurl }}">
                    {{ post.title }}
                </a>
            </h3>
            <p class="post-item__meta">
                {{ post.date | date: "%b %-d, %Y" }}
            </p>
        </li>
    {% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
