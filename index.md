---
layout: page
title: Phillip Smith
tagline: School of Computer Science
---
{% include JB/setup %}

Hi, my name is Phillip Smith, and I am a Research Student at the University of Birmingham, under the supervision of [Dr. Mark Lee](http://www.cs.bham.ac.uk/~mgl). 

I am interested in Natural Language Processing, in particular, Sentiment Analysis. My motivation is to contribute research into creating a general model of sentiment within text, which is independant of domain. I would hope that this model will handle some of the subtler forms of day-to-day language that we take for granted (yet contribute so much), such as metaphor. My interest in this field stems from a curiosity surrounding the length to which mining of textual data can go in producing unexpected conclusions, and revealing the great wealth that such data holds. 

In addition to my research, I am a Senior Teaching Associate, lecturing for MSc Fundamentals: Introduction to Computer Science, and for the second year BSc Software System Components and first year Language & Logic modules. I am also a member of the Research Committee. 
    
## Publications

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



