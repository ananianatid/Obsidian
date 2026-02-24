---
tags:
  - MOC
created: {{date}}
---

# 🤝 MOC — Contacts

Personnes et organisations.

## 👤 Personnes

```base
filters:
  - tags = "personne"
views:
  - type: table
    name: Personnes
    order:
      - file.name
```

## 🏢 Organisations

```base
filters:
  - tags = "organisation"
views:
  - type: table
    name: Organisations
    order:
      - file.name
```

