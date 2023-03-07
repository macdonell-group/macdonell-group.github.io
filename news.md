---
layout: page
title: News archive
---

{%- if site.posts.size > 0 -%}
  <p class="h2">{{ page.list_title | default: "News" }}</p>
  <ul class="list-unstyled">
    {%- for post in site.posts -%}
    <li>
      <span class="text-muted">
        {%- assign date_format = "%b %-d, %Y" -%}
        {{ post.date | date: date_format }}
      </span>
      <p class="h4">
        <a href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </p>
      {{ post.excerpt }}
    </li>
    {%- endfor -%}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p>
{%- endif -%}
