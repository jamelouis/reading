---
layout: default
title: Reading
reading_level: 3
---
<section class='content'>
    <h1 class="fb">Reading</h1>
    <p class="line"><span>You are what you read</span></p>
    <div class="flex-wrap">
        {% for topic in site.data.topics %}
        <div class="topic-block sky-bg">
            <a class="fs30 fb topic" href="{{ topic.url }}">{{ topic.name }}</a>
            <p>{{ topic.description }}</p>
        </div>
        {% endfor %}
    </div>
</section>
