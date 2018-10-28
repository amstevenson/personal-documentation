---
layout: example
title: Markdown
---
# Markdown Examples

```
    <div id="side-navigation">
      <nav>
        <ul>
          {% for example in site.examples %}
          <li><a href="{{site.baseurl}}{{example.url}}">{{ example.title }}</a></li>
          {% endfor %}
        </ul>
      </nav>
    </div>
```