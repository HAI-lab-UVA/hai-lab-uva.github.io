---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags="tag 1, tag 2, tag 3" %}

{% include search-info.html %}

# Featured

{% include list.html data="projects" component="projectcard" filters="group: featured" %}

{% include section.html %}

# More

{% include list.html data="projects" component="projectcard" filters="group: " style="small" %}
