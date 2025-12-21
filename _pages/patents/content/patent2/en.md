{% tab language-tabs-p3 English %}

> ##### WARNING
>
> Note: This content was originally written in Persian and translated into English using AI. Minor inaccuracies may exist.
{: .block-warning }

{% capture en_information -%}
{% include_relative content/patent2/en/information.md %}
{%- endcapture %}

{% capture en_summary -%}
{% include_relative content/patent2/en/summary.md %}
{%- endcapture %}

{% capture en_appendices -%}
{% include_relative content/patent2/en/appendices.md %}
{%- endcapture %}

{% tabs info-tabs-en %}
{% tab info-tabs-en Information %}
{{ en_information | markdownify }}
{% endtab %}

{% tab info-tabs-en Summary %}
{{ en_summary | markdownify }}
{% endtab %}

{% tab info-tabs-en Appendices %}
{{ en_appendices | markdownify }}
{% endtab %}
{% endtabs %}

{% endtab %}
