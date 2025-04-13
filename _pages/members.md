---
layout: page
permalink: /members/
title: Members
description:
nav: true
nav_order: 1
---

## Professors

<div class="row">
{% assign members = site.members | where: 'role', 'Professor' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}
</div>

## Research Scientistss

<div class="row">
{% assign members = site.members | where: 'role', 'Research Scientist' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}
</div>

## Postdoctoral Scholars

<div class="row">
{% assign members = site.members | where: 'role', 'Research Scientist' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}
</div>

## Graduate Students

<div class="row">
{% assign members = site.members | where: 'role', 'Graduate Student' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}
</div>

## Visitors

<div class="row">
{% assign members = site.members | where: 'role', 'Visiting Scholar' %}
{% for member in members %}
{{ member | slice: 106, 1000 }} <!-- HACK! -->
{% endfor %}
</div>

## Recent Alumni

- [Arjun Viswanathan, Ph.D. '24](https://homepage.cs.uiowa.edu/~viswanathn/). *Visiting assistant professor at Union College, Schenectady, NY*
- [Andrew Marmaduke, Ph.D. '24](https://uiowa.marmamorphism.com/#:~:text=Andrew%20Marmaduke). *Postdoctoral scholar at University of Iowa, Iowa City, IA*
- [Christa Jenkins, Ph.D. '23](https://cwjnkins.github.io/#:~:text=Postdoctoral). *Postdoctoral associate at Stony Brook University, Stony Brook, NY*

## Former members

See our [alumni page]({{ '/alumni/' | relative_url }}) for a full archive of alumni and former staff.
