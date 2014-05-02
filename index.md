---
title: Home Page
layout: front
---
{% include JB/setup %}

<div class="row-fluid">
  <div class="span5">
     <img width="160" alt="Martin Elsman" align="left" src="/images/elsman.jpg">
  </div>
  <div class="span7">
     Associate Professor<br />
     Department of Computer Science<br />
     University of Copenhagen<br />
     Universitetsparken 5, Building B<br />
     2100 Copenhagen Ø<br />
     Denmark<br /><br />
     mobile: +45 26122212<br />
     email: mael at di.ku.dk<br />
     office: 01-0-015<br /><br />

     <a href="http://www.hiperfit.dk">HIPERFIT</a> Center Manager.
  </div>
</div>


## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
