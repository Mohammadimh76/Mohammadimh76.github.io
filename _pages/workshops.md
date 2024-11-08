---
layout: page
title: workshops
permalink: /workshops/
description: organized workshops and competitions
nav: false
nav_order: 4
display_categories: [workshops, competitions]
horizontal: false
only_highlights: false
---

<div class="writing">
  {%- if site.enable_project_categories and page.display_categories -%}
    <!-- Display categorized workshops -->
    {%- for category in page.display_categories -%}
      <h2 class="category">{{ category }}</h2>
      
      {%- assign categorized_projects = site.workshops | where: "category", category -%}
      
      {%- if page.only_highlights -%}
        {%- assign categorized_projects = categorized_projects | where: "highlighted", true -%}
      {%- endif -%}

      <!-- Sort the workshops by 'importance' and 'date' -->
      {%- assign sorted_projects = categorized_projects | sort: 'importance' %}
      {%- assign sorted_projects = sorted_projects | sort: 'date' %}
      
      <div class="list-style mx-auto">
        {%- for project in sorted_projects -%}
          {% include workshops.liquid %}
        {%- endfor %}
      </div>
    {% endfor %}
  {%- else -%}
    <!-- Display workshops without categories -->
    {%- assign sorted_projects = site.workshops %}
    
    {%- if page.only_highlights -%}
      {%- assign sorted_projects = sorted_projects | where: "highlighted", true -%}
    {%- endif -%}

    <!-- Sort the workshops by 'importance' and 'date' -->
    {%- assign sorted_projects = sorted_projects | sort: 'importance' %}
    {%- assign sorted_projects = sorted_projects | sort: 'date' %}
    
    <div class="list-style mx-auto">
      {%- for project in sorted_projects -%}
        {% include workshops.liquid %}
      {%- endfor %}
    </div>
  {%- endif -%}
</div>
