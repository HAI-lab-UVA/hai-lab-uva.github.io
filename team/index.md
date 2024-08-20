---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Primary Investigator
{% include list.html data="members" component="portrait" filters="role: ^pi$" %}

## PhD Students
{% include list.html data="members" component="portrait" filters="role: ^phd$" %}

## Master's Students
{% include list.html data="members" component="portrait" filters="role: ^ms$" %}

## Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: ^undergrad$" %}

## Research Interns
{% include list.html data="members" component="portrait" filters="role: ^intern$" %}

## Staff
{% include list.html data="members" component="portrait" filters="role: ^staff$" %}

{% include section.html %}
# Alumni
Affiliations and contact information may not be up-to-date.

## PhD Students
{% include list.html data="members" component="portrait" filters="role: alum_phd" %}

## Master's Students
{% include list.html data="members" component="portrait" filters="role: alum_ms" %}

## Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: alum_undergrad" %}

## Research Interns
{% include list.html data="members" component="portrait" filters="role: alum_intern" %}

## Staff
{% include list.html data="members" component="portrait" filters="role: alum_staff" %}