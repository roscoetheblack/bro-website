---
layout: home
title: Building Websites with GitHub Pages
---

## Description
{{ site.description }}
{% assign lead = site.team_members | where:"role", "project lead" | first %}
The project is led by {{ lead.name }}.
[See our full team](about#team)
 
More details about the project are available from the [About page](about).

See some [examples of our work]({{ page.lesson-example }}).

Have any questions about what we do? [We'd love to hear from you!](mailto:{{ site.email }})

## Blog Posts

{% for post in site.blogposts %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url | relative_url }}) by {{post.author}}
{% endfor %}

{% include post_list.html %}

## Contact us

