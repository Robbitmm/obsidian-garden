---
layout: page
title: Home
id: home
permalink: /
---

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Não há gênio sem um toque de loucura. (Sêneca)
</p>

Notas pessoais sobre conhecimentos pessoais

<strong>Recently updated notes</strong>
<!-- {% for note in recent_notes limit: 5 %} -->

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
    <li>
      <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
