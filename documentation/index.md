---
layout: page
title: Equipment Documentation
excerpt: "Support blogs for Equipments"
search_omit: true
---

Tinkerers' Lab boasts an inventory ranging from tiny resistors to sophisticated machines like CNC Machines, 3D Printer, Heavy Machines like Lathe, Milling, Drill and necessary software assistance. For some of these, support documents have been prepared by generous inputs of lab users, to assist other users in using them.

---
<ul class="post-list">
{% for post in site.categories.tl_talks %}
  <li>
  	<documentation>
  		<a href="{{ site.url }}{{ post.url }}">
  			{{ post.title }}
  			<span class="entry-date">
  			<time datetime="{{ post.date | date_to_xmlschema }}">
  			{{ post.date | date: "%B %d, %Y" }}
  			</time>
  			</span>
  			{% if post.excerpt %}
  			<span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}
  			</span>
  			{% endif %}
  		</a>
  	</documentation>
  </li>
{% endfor %}
</ul>
