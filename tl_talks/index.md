---
layout: page
title: TL Talks
excerpt: "Tinkerers' Laboratory Talks"
search_omit: true

---

‘TL Talks’ have begun with the purpose of taking ahead the very spirit of innovation, by acquainting students with great technologies and the brains behind them, to inspire students to find the inventor within them.

---
<ul class="post-list">
{% for post in site.categories.tl_talks %}
  <li>
  	<article>
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
  	</article>
  </li>
{% endfor %}
</ul>
