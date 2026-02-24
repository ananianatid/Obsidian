---
tags:
  - MOC
created: {{date}}
---

# 🎬 MOC — Médias

Livres, séries, films, jeux vidéo.

## 📚 Livres

```base
filters:
  and:
    - file.hasTag("book")
    - '!file.hasProperty("quote")'
    - file.folder != "Template"
views:
  - type: table
    name: Table
    order:
      - file.name
      - author

```

## 🎬 Films & Séries

```base
filters:
  - tags = "show"
views:
  - type: table
    name: Shows
    order:
      - status
      - rating
```

## 🎮 Jeux vidéo

```base
filters:
  - tags = "game"
views:
  - type: table
    name: Jeux
    order:
      - status
      - rating
```

