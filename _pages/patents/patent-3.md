---
layout: page
permalink: /patents/patent3
title: patent55
nav: false
nav_order: 5
related_posts: false
tabs: true
---

{% tabs language-tabs-p3 %}

  {# English tab: load external Markdown, convert to HTML #}
  {% tab language-tabs-p3 English %}
    {% capture lang_en %}
      {% include_relative content/patent3/en.md %}
    {% endcapture %}
    {{ lang_en | markdownify }}
  {% endtab %}

  {# German tab: same pattern for the German content file #}
  {% tab language-tabs-p3 Germany %}
    {% capture lang_de %}
      {% include_relative content/patent3/de.md %}
    {% endcapture %}
    {{ lang_de | markdownify }}
  {% endtab %}

  {# Persian tab: wrap content in RTL container for right-to-left styling #}
  {% tab language-tabs-p3 Persian %}
    <div class="rtl-tab">
      {% capture lang_fa %}
        {% include_relative content/patent3/fa.md %}
      {% endcapture %}
      {{ lang_fa | markdownify }}
    </div>
  {% endtab %}
  
{% endtabs %}
