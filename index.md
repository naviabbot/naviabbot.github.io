---
layout: default
title: Navi's char hub
---
#Navi's Char Hub

###Links to the characters  
__Universal__  
[Navicia Abbot](/navi)  
  
__Aelflaed__  
[Yingying Univerba](/mizu)  
[Aretha Univerba](/camelot)  
  
__Androids__  
###Journal Entries

{% for post in site.posts %}
{{ post.date | date_to_string }}  [{{ post.title }}]({{post.url}})
{% endfor %}
