---
layout: page
title: Home
id: home
permalink: /
---

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Não há gênio sem um toque de loucura. (Sêneca)
</p>

O projeto se encontra na versão beta de testes
Alguns bugs relacionados à formatação e aos links estão sendo corrigidos.  

<strong>Últimas atualizações</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes%}
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
