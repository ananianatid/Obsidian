---
tags:
  - MOC
created: {{date}}
---

# 💼 MOC — Projets

Vue d'ensemble de tous les projets.

## 🚀 Projets actifs

```base
filters:
  and:
    - tags = "projet"
    - status = "in-progress"
views:
  - type: table
    name: En cours
    order:
      - deadline
```

## 📋 Tous les projets

```base
filters:
  - tags = "projet"
views:
  - type: table
    name: Tous
    order:
      - status
      - deadline
```

