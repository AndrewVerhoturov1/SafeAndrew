# Указатель инструкций агентов SafeAndrew

## Начальный маршрут

1. Прочитать `AGENTS.md`.
2. Для capture-only записи питания/стомы использовать специальный короткий маршрут из `AGENTS.md`.
3. Для остальных задач прочитать `system/repo-context.yaml`.
4. Открыть нужный `STATUS.md`, если задача относится к медицинскому направлению.
5. Выбрать инструкцию по виду задачи.

## Действующие инструкции

| Задача | Путь |
|---|---|
| Быстрая запись питания и стомы | `.agents/skills/capture-food-stoma-entry/SKILL.md` |

## Планируемые инструкции

| Задача | Будущий путь |
|---|---|
| Перенос медицинского документа | `.agents/skills/import-medical-document/SKILL.md` |
| Разбор лабораторного анализа | `.agents/skills/analyze-laboratory-result/SKILL.md` |
| Исследование медицинской гипотезы | `.agents/skills/research-medical-hypothesis/SKILL.md` |
| Обновление схемы лекарств | `.agents/skills/update-medication-plan/SKILL.md` |
| Подготовка сводки для врача | `.agents/skills/prepare-doctor-brief/SKILL.md` |
| Разбор ежедневных записей | `.agents/skills/daily-health-review/SKILL.md` |

> [!NOTE]
> Инструкции создаются постепенно. Агент не должен выдумывать отсутствующую инструкцию или утверждать, что выполнил её.
