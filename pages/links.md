---
layout: mypost
title: Links
---
Functionality not yet available

```
Name：{{ site.title }}
Descriptio：{{ site.description }}
URL：{{ site.domainUrl }}{{ site.baseurl }}
Avatar：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.jpg
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
