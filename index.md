---
layout: default
title: "Index"
---

## Where am I?

You are on **SNVMK**`s homepage. You can find my projects and info about me!

## Projects

### SNVMDB

[Simplest databases management tool.](https://snvmk.tk/snvmdb/ "Link to quick overview")

### Discord Bots

[Order a bot](https://snvmk.tk/bots/)
[SlashBot](https://snvmk.tk/bots/slash)
[NekoBot](https://snvmk.tk/bots/neko)

## Posts

{% for post in site.posts %}

[{{ post.title }}]({{post.url}})

{% endfor %}

{% include footer.md %}
