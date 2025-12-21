---
layout: page
permalink: /patents/patent2
title: Test7
nav: false
nav_order: 5
related_posts: false
tabs: true
---


{% tabs language-tabs-p3 %}

{% tab language-tabs-p3 English %}
{% capture lang_en -%}
{% include_relative content/patent2/en.md %}
{%- endcapture %}
{{ lang_en | markdownify }}
{% endtab %}

{% tab language-tabs-p3 Persian %}
<div class="rtl-tab">
{% capture lang_fa -%}
{% include_relative content/patent2/fa.md %}
{%- endcapture %}
{{ lang_fa | markdownify }}
</div>
{% endtab %}

{% endtabs %}






