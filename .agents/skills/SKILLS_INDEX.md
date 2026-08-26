# Указатель инструкций агентов SafeAndrew

## Начальный маршрут

1. Прочитать `AGENTS.md`.
2. Прочитать `system/repo-context.yaml`.
3. Открыть нужный `STATUS.md`, если задача относится к конкретному медицинскому направлению.
4. Выбрать инструкцию по виду задачи.

## Инструкции по видам задач

| Задача | Путь |
|---|---|
| Перенос медицинского документа | `.agents/skills/import-medical-document/SKILL.md` |
| Разбор лабораторного анализа | `.agents/skills/analyze-laboratory-result/SKILL.md` |
| Исследование медицинской гипотезы | `.agents/skills/research-medical-hypothesis/SKILL.md` |
| Построение научной библиотеки | `.agents/skills/build-scientific-library-document/SKILL.md` |
| Обновление схемы лекарств | `.agents/skills/update-medication-plan/SKILL.md` |
| Подготовка сводки для врача | `.agents/skills/prepare-doctor-brief/SKILL.md` |
| Разбор ежедневных записей | `.agents/skills/daily-health-review/SKILL.md` |

> [!NOTE]
> Инструкции создаются постепенно. Перед использованием пути агент должен убедиться, что соответствующий `SKILL.md` существует. Нельзя выдумывать отсутствующую инструкцию или утверждать, что она была выполнена.