---
title: Ginger Hawthorne
---
<style>
	#accounts li {
		float: left;
		width: 25%;
		padding: .5rem 0;
		text-align: center;
		list-style: none;
	}
</style>
{{ site.url }}
{{ site.data }}
<ul id="accounts">
{% for account in site.data.accounts %}
	<li><a rel="me" href="{{ account.url }}">{{ account.name }}</a></li>
{% endfor %}
</ul>
