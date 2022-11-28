---
title: Programme
---

Leider sind nicht alle Programme, die an der OST eingesetzt werden, auf Linux & Co verfügbar.
Darum haben wir dir hier Alternativen aufgelistet.

## Übersicht
Programm        | Empfohlene Alternative            |       Weitere Alternativen
----------------|-----------------------------------|----------------------------
Outlook         | [Thunderbird](/app/thunderbird)   | [Evolution](https://wiki.gnome.org/Apps/Evolution/), Mac Mail, Claws-Mail
HSR Mapper      | [open\HSR Connect](https://github.com/openhsr/connect) | [Kommandozeilen-Scripts](https://gist.github.com/raphiz/29dd1ed3145b06b9398d)
[DASYLab](/tipps/dasylab) (Modul ICTh)			| keine / Verwendung mit [Wine](/tipps/wine) 	| -

{% for app_page in site.app %}

  <h2>{{ app_page.teaser_title }}: {{ app_page.title }}</h2>
  <p>{{ app_page.teaser }}</p>
  <p>&#8618; <a href="{{ app_page.url }}">Mehr zu {{ app_page.title }}</a></p>
  {% if app_page.teaser_image %}
  <img src="{{ app_page.teaser_image }}" />
  {% endif %}

{% endfor %}


Fehlt dir etwas? [Dann gib uns Bescheid!](/hilfe/)
