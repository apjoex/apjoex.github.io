---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">

<ul style=" text-align:center; display:block; margin-left:auto; margin-right:auto">

<li style="margin-left:5px; margin-right:5px; display: inline;">
<a href="https://twitter.com/{{ site.twitter_username }}">
      <i class="fa fa-twitter"></i> Twitter
    </a>
</li>

<li style="margin-left:5px; margin-right:5px; display: inline;">
<a href="https://github.com/{{ site.github_username }}">
      <i class="fa fa-github"></i> GitHub
    </a>
</li>

</ul>

Here is a list of the few things I've written 👇
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
