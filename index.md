---
layout: default 
title: kokotech
---
<div class="page-title">
  kokotech
</div>
<div class="page-explanation">
  Tech memo by <a href="https://twitter.com/deepneko">@deepneko</a><br>
  See also <a href="http://blog.kokonani.com">kokonani</a>, <a href="https://github.com/deepneko">github</a>
</div>
{% for page in site.posts limit:5 %}
<hr>
<div class="page-header">
  <h1><a href='{{ page.url }}'>{{ page.title }}</a> {% if page.tagline %}<small>{{page.tagline}}</small>{% endif %}</h1>
  <h4 style="display:inline">{{ page.date | date_to_string }}</h4>
  {% unless page.tags == empty %}
  <ul class="tag_box inline" style="padding-left: 0px;">
    {% assign tags_list = page.tags %}
    {% include JB/tags_list %}
  </ul>
  {% endunless %}  
</div>

<div class="row post-full">
  <div class="col-xs-12">
    <div class="content">
      {{ page.content }}
    </div>
  </div>
</div>
{% endfor %}
