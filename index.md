---
layout: default
title: Home
---

## Welcome to my tutorial          
## [Training on Next generation sequencing ](https://bioinfo-dirty-jobs.github.io/NGSBASE/)

___

#### Here you can find a tutorials collection to support the course.

{::nomarkdown}

{% assign pages_list = site.pages | sort:"url" %}
    {% for node in pages_list %}
      {% if node.title != null %}
        {% if node.layout == "page" %}
          <a class="sidebar-nav-item{% if page.url == node.url %} active{% endif %}" href="{{site.url}}{{ node.url }}">{{ node.title }}
          <p class="note">{{node.summary}}</p></a>
        {% endif %}
      {% endif %}
    {% endfor %}
{:/}


### Authors and Contributors

 * [Polano Maurizio](mauriziopolano@blu.it)


### Acknowledgement
 
I would like to say thank you to  Gianmauro Cuccuru for the great help.

### Contributing

If you've found mistakes or any other kind of material you think should be shared through this repository you can:

1. Fork this repository.
2. Add your content on the appropriate page.
3. Commit your changes.
4. Submit a pull request.
