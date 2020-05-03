---
title: "Adrien Joly — Musician"
---

## Releases and contributions

<!-- listed from _data/tracks.yaml -->

{% for track in site.data.tracks %}
- {{ track.name }} ({{ track.contributions | join: “, “ }})
{% endfor %}

{% comment %}
({% include render_contributions.html list=track.contributions %})
{% endcomment %}
