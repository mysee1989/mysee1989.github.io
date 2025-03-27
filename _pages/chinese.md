---
layout: default
permalink: /
title: ""
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes_zh/biography.md %}

<span class='anchor' id='selected-publications'></span>
{% include_relative includes_zh/publications.md %}

<span class='anchor' id='education'></span>
{% include_relative includes_zh/education.md %}

<span class='anchor' id='experience'></span>
{% include_relative includes_zh/experience.md %}

<span class='anchor' id='honors'></span>
{% include_relative includes_zh/honors.md %}

<span class='anchor' id='services'></span>
{% include_relative includes_zh/services.md %}