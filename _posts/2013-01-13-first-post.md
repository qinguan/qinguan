---
layout: post
title: hello world
---
<nav>
	{% if page.previous %}<a rel="prev" href="{{ site.baseurl }}{{ page.previous.url }}">&larr; previous</a>{% endif %}
	{% if page.next %}<a rel="next" href="{{ site.baseurl }}{{ page.next.url }}">next &rarr;</a>{% endif %}
</nav>
{{ page.title }}
{{page.date | date_to_string }}

ÄãºÃ£¡£¡£¡
