---
title: "Index"
---

## Where am I?

You are on **SNVMK**`s homepage. You can find my projects and info about me!

## Projects

### SNVMDB

[Simplest databases management tool.](https://snvmk.tk/snvmdb/snvmdb.html "Link to quick overview")

## Posts

{% for post in site.posts %}

[{{ post.title }}]({{post.permalink}})

{% endfor %}

{% include footer.md %}
