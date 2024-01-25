---
layout: page
title: Home
id: home
permalink: /
---

# Benvenuto! 🌱

Questo è il [giardino digitale] di Zeruhur.

Se vuoi installarne uno tuo ecco una [guida passo passo per farlo](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll) (in inglese).

<strong>Note aggiornate di recente:</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
