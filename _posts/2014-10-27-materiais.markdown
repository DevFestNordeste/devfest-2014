---
layout: post
title:  "Materiais de palestras"
date:   2014-10-28 18:00:00
isStaticPost: false
---

Foi em alguma palestra e gostaria de relembrar algum slide? Listamos abaixo os materiais disponibilizados pelos palestrantes. Se sentir falta de alguma coisa, basta comentar.

{% for session in site.data.sessions %}
{% if session.links != null %}
- **{{session.title}}**
	{% for item in session.links %}
	[{{item.description}}]({{item.url}})
	{% endfor %}
{% endif %}
{% endfor %}