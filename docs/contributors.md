---
layout: page
navigation_title: Contributors
title: Contributors
permalink: /contributors/
button: true
cover: 'https://mozillatn.github.io/clubs/assets/mozilla-tn-bannerc.png'
---

Here are the list of amazing Mozilla contributors from our club.

<h3>Present Contributors</h3>
<div class="contributors_wrapper">
{% for contributor in site.data.present_contributors %}
<div class="contributors">

<div class="pic" style="height: 130px; width: 130px">
<img src="{{ contributor.photo }}"></div><br>
<p class="name">Name: {{ contributor.name }}</p>
<p class="contribution">Contribution Area: {{ contributor.contribution }}</p>
	

</div>

{% endfor %}
</div>
<h3>Past Contributors</h3>
<div class="contributors_wrapper">
{% for contributor in site.data.past_contributors %}
<div class="contributors">

<div class="pic" style="height: 130px; width: 130px">

<img src="{{ contributor.photo }}"></div><br>

<p class="name">Name: {{ contributor.name }}</p>
<p class="contribution">Contribution Area:{{ contributor.contribution }}</p>

</div>
{% endfor %}
</div>
