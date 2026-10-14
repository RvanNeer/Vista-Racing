# Vista Racing – website

Website van het H2GP-team van VISTA college: **https://rvanneer.github.io/Vista-Racing/**

De site wordt automatisch gebouwd door GitHub Pages (Jekyll). Je hoeft niets te installeren:
een wijziging opslaan (committen) op GitHub is genoeg; na 1 à 2 minuten staat hij online.

## Tekst aanpassen

| Pagina | Bestand |
|---|---|
| Home | `index.md` |
| De auto | `auto.md` |
| Waterstof | `waterstof.md` |
| Team | `team.md` |
| Menu en sitenaam | `_config.yml` |

Open het bestand op github.com, klik op het potloodje (✏️ *Edit*), pas de tekst aan en klik op **Commit changes**.

De tekst is **Markdown**:

```markdown
## Kopje
Gewone tekst. **Vet** en *schuin*.

- opsomming
- nog een punt

[Een link](https://www.vistacollege.nl)
![Foto van de auto](/Vista-Racing/assets/img/auto.jpg)
```

## Nieuwsbericht toevoegen

1. Ga naar de map `_posts` en kies **Add file → Create new file**.
2. Noem het bestand `JJJJ-MM-DD-korte-titel.md`, bijvoorbeeld `2026-11-02-eerste-testrit.md`.
3. Begin het bestand met:

```markdown
---
layout: post
title: Eerste testrit
---

Hier komt de tekst van het bericht.
```

## Foto's toevoegen

Ga naar `assets/img`, kies **Add file → Upload files** en sleep de foto erin.
Gebruik daarna in een pagina: `![Omschrijving](/Vista-Racing/assets/img/bestandsnaam.jpg)`.
Tip: maak foto's eerst kleiner (max. ± 1600 px breed) zodat de site snel blijft.
