---
layout: page
title:  'Daily Dose for October 2017'
date:   2017-10-01 00:00:00 -0400
excerpt_separator: <!--more-->
comments: true
published: true
navigation: '<< Daily Dose for [September 2017](/daily/2017/09/) &#124; [2017](/daily/2017/) &#124; Daily Dose for November 2017 >>'
pubdays: 
    - day: 2017.10.01
      path: /daily/2017/10/01/
---
{{page.navigation}}
<hr/>

## Published Dates
<ul>
  {% for item in page.pubdays %}
    <li><a href="{{ item.path }}">Daily Dose for {{ item.day }}</a></li>
  {% endfor %}
</ul>

<hr/>
{{page.navigation}}
