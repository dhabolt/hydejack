---
layout: page
title:  'Daily Dose for September 2017'
date:   2017-09-01 00:00:00 -0400
excerpt_separator: <!--more-->
comments: true
published: true
navigation: '<< Daily Dose for August 2017 &#124; [2017](/daily/2017/) &#124; Daily Dose for October 2017 >>'
pubdays: 
    - day: 2017.09.20
      path: /daily/2017/09/20/
    - day: 2017.09.19
      path: /daily/2017/09/19/
    - day: 2017.09.18
      path: /daily/2017/09/18/
    - day: 2017.09.17
      path: /daily/2017/09/17/
    - day: 2017.09.16
      path: /daily/2017/09/16/
    - day: 2017.09.15
      path: /daily/2017/09/15/
    - day: 2017.09.14
      path: /daily/2017/09/14/
    - day: 2017.09.13
      path: /daily/2017/09/13/
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
