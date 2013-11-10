---
layout: page
title: IB News
tagline: From Iceland's IB Programme
---
{% include JB/setup %}

## Note From the Editor
 
To the IB students of MH (and anyone else with an interest in student newspapers),

Thank you for reading the IB News. Due to the currently-demanding schedule for us IB 2 students, the paper's release was slightly delayed. However, expect new articles to appear regularly from now on.
You may be wondering what this newspaper is exactly. The IB News brings its readers relevant news, activities, and opinions, all brought forth in a professional manner. In comparison to a regular newspaper, these articles attempt to cover more at once while still being accessible and informative.
If you're an IB student and would like to write for this newspaper, please let me know. The more writers, the better the newspaper. You could either write sporadically or become a full-time writer for us—both would be appreciated.
Enjoy the paper.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Björn Björnsson

===================================================================================


Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
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


