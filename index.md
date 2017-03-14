---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<style>
.ul_block {
  padding: 0;
  margin: 0;
  display: block;
  text-align: center;
}

.ul_block li {
  display: inline;
      padding: 0 10px;
}
</style>


<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">

<ul class="ul_block">

<li>
<a href="https://twitter.com/{{ site.twitter_username }}">
      <i class="fa fa-twitter"></i> Twitter
    </a>
</li>

<li>
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
