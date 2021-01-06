---
layout: page
permalink: /talks/
title: talks
nav: talks
description: talks, lectures and poster presentations
---

<!-- News -->
<div class="news mt-3 p-0">
  {% assign talks = site.talks | reverse %}
  {% for item in talks %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge info-color-dark font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div>
