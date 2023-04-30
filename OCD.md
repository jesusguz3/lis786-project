---
title: OCD
layout: page
permalink: /ocd
---
On this page, you will find information all about OCD, welcome!!!



{% for symptom in site.symptoms %}
{% if symptom.category == 'symptoms' %}
<h2>{{ symptom.title }}</h2>
<p><img src="{{ symptom.image }}" /></p>
<p>{{ symptom.content }}</p>
{% endif %}
{% endfor %} 


Hi!

<p>Category: {{ symptom.category }}</p>