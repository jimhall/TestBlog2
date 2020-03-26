# Welcome to my blog

I'm glad you are here. I plan to talk about ...

This is the second pathetic attempt to add content and figure out how Jekyll
works.

	  {% for post in site.posts %}
	    * {{ post.date | date_to_string }} » [{{ post.url }}] ({{ post.title }})
	  {% endfor %}

