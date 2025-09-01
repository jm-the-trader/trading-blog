---
layout: page
title: Journal
permalink: /journal/
---

## Trade Journal

Below are your latest trade entries. Add new entries as markdown files in the `_posts` folder.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}
{% endfor %}
