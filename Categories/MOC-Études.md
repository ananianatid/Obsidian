---
tags:
  - MOC
created: {{date}}
---

# 🎓 MOC — Études

Vue d'ensemble de toutes les UE et notes de cours.

## 📚 Unités d'Enseignement

```base
filters:
  - tags = "UE"
  - tags = "wrapper"
views:
  - type: table
    name: UE
    order:
      - semester
      - file.name
```

## 🔗 Notes récentes

```base
filters:
  - tags = "UE"
  - tags = "note"
views:
  - type: table
    name: Notes
    order:
      - created
```

