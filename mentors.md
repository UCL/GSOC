---
layout: default
title: Mentors
permalink: /mentors/
short: mentors
mentors:
 sinan:
  nick: sinanshi
  name: Sinan Shi
 david:
  nick: dpshelio
  name: David Perez-Suarez
---
# Who are we?

{% for mentor in page.mentors %}
<a href="http://github.com/{{mentor[1]['nick']}}"><img style="border-radius:10px; width:50px" src="http://github.com/{{mentor[1]['nick']}}.png?size=50"> {{mentor[1]["name"]}} </a> <br>
{% endfor %}
