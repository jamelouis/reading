---
layout: default
title: Reading
reading_level: 3
---
<section class='content'>
    <h1 class="fb">Reading</h1>
    <p class="line"><span>You are what you read</span></p>
    <ul class="flex-wrap">
        {% for topic in site.data.topics %}
        <li class="topic-block">
            <a class="fs30 fb topic" href="{{ topic.url }}">{{ topic.name }}</a>
            <p>{{ topic.description }}</p>
        </li>
        {% endfor %}
    </ul>
</section>
