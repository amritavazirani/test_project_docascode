---
layout: template_demo
author:  Making the most of DITA
---

# Home page

I authored the booked named {{ page.author }}.

The book was written in the year {{ site.when }}.

The book provides information about the following:

# Basics of DITA 
# Make optimum use of available resources
# Reference material available online

In addition to this, here are the names of some bestselling books authored by me:

{% for item in site.data.books %}
- {{ item.books }}: {{ item.year }}
{% endfor %}
 
  



