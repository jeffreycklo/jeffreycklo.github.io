---
layout: page
title: Hello!
permalink: /about/
published: true
redirect_from: "/"
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

I help build self-service analytical capability within internal functions, to help business users make data-informed decisions. Within my current role, I engage with various senior stakeholders to provide innovative solutions around their data and reporting needs. I'm very passionate about analytics and visualisation, specialising in data modelling and building analytical dashboards.

On the side, I enjoy teaching technical skills (such as data modelling, visual analytics, data visualisation, business process modelling). A list of units I have taught, including guest lectures, can be found in the [teaching tab](https://jeffreycklo.github.io/teaching).

Connect with me on [LinkedIn](https://www.linkedin.com/in/jeffreycklo/)!

</div>
