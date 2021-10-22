---
layout: default
title: Past Talks
---

<div class="toc">
  <ul class="texts">
    {% assign sorted = site.pasttalks | sort:"time" | reverse %}
    {% for item in sorted %}
    
    <li class="text-title"> {{item.time}}
      <a href={{ item.homepage }}>{{ item.author }}</a> : 
      <a href="{{ site.baseurl }}{{ item.url }}"> {{ item.title }}</a>
    </li>
    {% endfor %}
  </ul>
</div>
