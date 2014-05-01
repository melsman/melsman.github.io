---
title: Home Page
layout: front
---
{% include JB/setup %}

<div class="row-fluid">
  <div class="span4">
     <img width="150" alt="Martin Elsman" align="left" src="/images/elsman.jpg">
  </div>
  <div class="span4">
     Associate Professor

     Department of Computer Science

     University of Copenhagen, Denmark

     Universitetsparken 5, Building B, gr.

     2100 Copenhagen Ø

     mobile: +45 26122212

     email: mael at di.ku.dk

     office: 01-0-015

     [HIPERFIT](http://www.hiperfit.dk) Center Manager.
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
