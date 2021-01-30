---
title: Главная
gh-badge: [star]
---

# Добро пожаловать на сайт СНВМК!

Вы находитесь на сайте СНВМК - ~~тупого школоло~~ кулхацкера сайтов и ботов в Discord.

# Посты

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.subtitle }}
{% endfor %}

<script src="https://utteranc.es/client.js"
        repo="SNVMK/snvmk.github.io"
        issue-term="title"
        label="Комментарии"
        theme="github-dark"
        crossorigin="anonymous"
        async>
</script>
