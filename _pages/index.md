---
layout: default
avatar: true
permalink: /
---
## **🚀 Hello readers**
### _Welcome to my blog,_

### The following are my recent blogs, hope you will like it :)

{% for post in site.posts limit: 5 %}<a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a><br>{% endfor %}
---
