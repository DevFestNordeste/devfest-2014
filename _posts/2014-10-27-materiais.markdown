---
layout: post
title:  "Materiais de palestras"
date:   2014-10-27 18:00:00
isStaticPost: false
---

Foi em alguma palestra e gostaria de relembrar algum slide? Listamos abaixo os materiais disponibilizados pelos palestrantes. Se sentir falta de alguma coisa, basta comentar.

{% for session in site.data.sessions %}
- {{session.title}}
{% endfor %}