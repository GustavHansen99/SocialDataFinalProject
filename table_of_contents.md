---
layout: page
title: Table of Contents
permalink: /ToC/
weight: 1
---

<div class="page">
  {%- if site.posts.size > 0 -%}
    <h2 class="post-list-heading">{{ page.list_title | default: "Table of Contents" }}</h2>
    <ul class="post-list">
      {%- for post in site.posts -%}
      <li>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
    </ul>
    {%- endif -%}
</div>

