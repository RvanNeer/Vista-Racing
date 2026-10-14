---
layout: default
title: Home
hero:
  label: H2GP · VISTA college
  titel: Racen op waterstof
  tekst: Wij bouwen een radiografisch bestuurde auto die rijdt op een waterstof-brandstofcel. Op deze site lees je hoe de auto werkt, wat we leren en hoe het team ervoor staat.
---

## Wat is H2GP?

H2GP (Hydrogen Grand Prix) is een wedstrijd voor scholieren en studenten met RC-auto's op schaal 1:10 die rijden op waterstof. Een brandstofcel zet waterstof om in elektrische energie. Het doel is zo ver mogelijk te rijden met een beperkte hoeveelheid waterstof. Slim omgaan met energie is dus net zo belangrijk als snelheid.

<div class="kaarten">
  <div class="kaart">
    <h3>De auto</h3>
    <p>Chassis, motor, regelaar en de energievoorziening.</p>
    <a href="{{ '/auto/' | relative_url }}">Lees meer →</a>
  </div>
  <div class="kaart">
    <h3>Waterstof</h3>
    <p>Hoe een brandstofcel werkt en hoe we veilig tanken.</p>
    <a href="{{ '/waterstof/' | relative_url }}">Lees meer →</a>
  </div>
  <div class="kaart">
    <h3>Nieuws</h3>
    <p>Updates uit de werkplaats en van wedstrijden.</p>
    <a href="{{ '/nieuws/' | relative_url }}">Lees meer →</a>
  </div>
</div>

## Laatste nieuws

<ul class="nieuwslijst">
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <div class="meta">{{ post.date | date: '%d-%m-%Y' }}</div>
  </li>
{% endfor %}
</ul>
