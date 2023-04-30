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
<p>Category: {{ symptom.category }}</p>
{% endif %}
{% endfor %} 


# More on obsessions

When you have OCD, you experience obsessions. These obsessions are constant, undesired thoughts, or images that are intrusive and cause a great amount of stress and anxiety. It's common to try to ignore these unwanted thoughts, or you might even perform a compulsive ritual or behavior to get rid of them. This only causes temporary relief, and the thoughts come back. However, many people do realize that their thoughts make no sense, but the thought still persists. Obsessions can take up a lot of a person's time.

**Other common symptoms for obsessions**
* Fear of being contaminated with body fluids, diseases, household chemicals
* Violent impulses
* Identity obsession
* Being perfect in everything you do

