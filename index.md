---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">

<div style="align:center">
<i class="fa fa-twitter" aria-hidden="true"></i>[@apjoex](https://twitter.com/apjoex)
<i class="fa fa-github" aria-hidden="true"></i>[@apjoex](https://github.com/apjoex)
</div>

Here is a list of the few things I've written 👇
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
