---
id: metadata-schema
ntype: system-rule
status: active
updated: 2026-07-28
---

# Схема свойств документов

## Обязательные свойства

```yaml
---
id: permanent-latin-id
ntype: document-type
status: draft
updated: 2026-07-28
---
```

## Основные типы `ntype`

- `navigation`
- `primary-medical-document`
- `medical-summary`
- `domain-status`
- `symptom`
- `medical-test`
- `medication`
- `scientific-review`
- `hypothesis`
- `daily-health-log`
- `appointment`
- `system-rule`

## Дополнительные свойства

```yaml
date: 2026-02-05
body_system:
  - nervous-system
conditions:
  - polyneuropathy
source_kind: primary-medical-document
confidence: confirmed
aliases:
  - ЭНМГ
  - электронейромиография
```

## Правила

- `id` не менять после создания.
- Даты хранить как `YYYY-MM-DD`.
- Видимые названия файлов — на русском.
- Машинные значения полей — короткие и стабильные.
