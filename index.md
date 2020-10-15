---
title: Home
---

# Welcome to the Impact Evaluation Training!

{% include figure.html img="3ie_logo.png" alt="intro image here" caption="Library workshop" width="75%" %}


*Add your workshop abstract here!*



<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

Hosted by [International Initiative for Impact Evaluation](http://www.3ieimpact.org/), {{ site.pub_year }}.

> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
