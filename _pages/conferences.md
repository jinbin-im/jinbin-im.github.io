---
layout: page
permalink: /conferences/
title: conferences
description: conferences by categories in reversed chronological order.
nav: true
nav_order: 3
---

<style>
.conf-location {
  display: inline-block;
  background: #7b27d8;
  color: white;
  padding: 4px 12px;
  border-radius: 15px;
  font-size: 0.85rem;
  font-weight: 500;
  margin-left: 10px;
}

.conf-title a {
  color: inherit;
  text-decoration: none;
}

.conf-title a:hover {
  color: #7b27d8;
}
</style>

<div class="publications">
  {% bibliography --file conferences --template bib_conference %}
</div>
