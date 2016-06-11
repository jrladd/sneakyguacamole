---
layout: page
title: Recipes
permalink: /recipes/
---

### Meals

{% for post in site.tags.meals %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

###Pastas

{% for post in site.tags.Pastas %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

{% for post in site.tags.pastas %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

###Soups, Stews, and Chilis
{% for post in site.tags["soups/stews"] %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

### Snacks, Sides, and Appetizers

{% for post in site.tags["snacks/sides"] %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

### Baked Goodies and Desserts
{% for post in site.tags.desserts %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

{% for post in site.tags["baked goodies"] %}
{{ post.date | date: "%b %-d, %Y" }}: [{{ post.title }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

