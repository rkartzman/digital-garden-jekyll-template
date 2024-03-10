---
layout: page
title: Home
id: home
permalink: /
---

*sotto vocce*. More [[about|about me]].

<strong>writing</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes %}
	  {% unless note.title == 'Your first seed' %}
	    <li>
	      {{ note.last_modified_at | date: "%Y-%m" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
	    </li>
	{% endunless %}
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
