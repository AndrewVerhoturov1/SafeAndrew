---
id: derived-dillingham-reference-methods-2016-ru
ntype: scientific-review
status: active
updated: 2026-10-05
source_kind: derived-structured-extract
source_stage: 2
derived_from:
  - source-dillingham-reference-methods-2016-card
language: ru
confidence: methodology-derived
tags:
  - ЭНМГ
  - NCS
  - референсные-значения
  - стандартизация
---

# Dillingham 2016 — качество референсных значений NCS — русский разбор

> [!IMPORTANT]
> Этап 2. Не официальный перевод.
>
> Канонический источник: [[07 Научная база/Источники/Dillingham 2016 — качество референсных значений NCS — карточка источника]].

## 1. Главный вопрос

Когда внешние reference values NCS достаточно качественны, чтобы их можно было использовать вне исходной лаборатории?

Ответ NDTF: только если нормативное исследование достаточно большое, правильно сформировало normal population, стандартизировало технику и использовало корректную статистику.

## 2. Семь фильтров качества

| № | Требование | Что проверять агенту |
|---|---|---|
| 1 | современная публикация/оборудование | исследование после 1990, digital EMG |
| 2 | sample >100 healthy subjects | хватает ли выборки для tail percentiles |
| 3 | настоящая normal cohort | асимптомные люди, правильные exclusions |
| 4 | техническая стандартизация | temperature, electrodes, distances, filters, display settings |
| 5 | возраст | широкий взрослый диапазон, elderly represented |
| 6 | статистика | age effects, distribution, percentiles, absent responses |
| 7 | представление | явные usable reference cut-offs |

## 3. Почему 'норма из учебника' может быть неправильной

Одна и та же цифра не универсальна, если различаются:

- stimulation/recording distance;
- electrode placement;
- filter settings;
- temperature;
- equipment;
- age/height/BMI состава reference cohort.

Поэтому при экспертном пересмотре SafeAndrew приоритет норм такой:

1. reference values конкретной лаборатории для использованного protocol;
2. валидированный внешний источник, методически совпадающий с protocol;
3. только затем общий справочник.

Эта иерархия — рабочее правило SafeAndrew, основанное на принципах NDTF.

## 4. Температура

Dillingham 2016 подтверждает, что холод:

- снижает conduction velocity;
- удлиняет latency;
- повышает amplitude.

Указанные общие диапазоны:

- upper 32–36°C;
- lower 30–36°C.

Это согласуется с отдельным техническим слоем температуры, но не отменяет различий thresholds между EAN/PNS и поздними AANEM-документами.

## 5. Расстояния

Ошибка измерения distance прямо влияет на calculated velocity.

Поэтому нужно знать:

- distal distance;
- segment length;
- точные stimulation/recording sites.

Если между двумя годами техника расстояний неизвестна/разная, прямое сравнение скорости должно иметь lower confidence.

## 6. Filter settings

High- и low-frequency filters способны менять:

- onset latency;
- amplitude.

Следовательно, отдельные специальные criteria, зависящие от CMAP duration или waveform shape, нельзя надёжно применять, если аппаратные настройки неизвестны.

## 7. SNAP и низкая амплитуда

Сенсорные ответы очень малы по сравнению с motor responses.

При низком SNAP:

- нужно отличать true response от artifact/captured motor activity;
- важна воспроизводимость;
- при <5 мкВ signal averaging нескольких responses может уменьшать noise.

Практический смысл для старых исследований: `response absent` или `very low SNAP` имеет больше веса, если raw waveform и техника показывают, что ответ действительно искали корректно.

## 8. Возраст и антропометрия

Age, height и BMI могут влиять на параметры.

Поэтому норму нельзя применять без понимания:

- возраста reference cohort;
- age adjustment;
- height/BMI adjustment там, где он статистически значим.

## 9. Статистическая ловушка

Многие NCS distributions не нормальны.

Поэтому:

- Gaussian assumptions могут быть неправильны;
- percentile-based cut-offs часто предпочтительнее;
- необходимо знать, как именно получен LLN/ULN.

## 10. Что это меняет в SafeAndrew

Для каждой старой ЭНМГ в сравнительной таблице нужно отдельное поле:

`reference source / laboratory norms known?`

Варианты:

- **да, локальные нормы и техника известны**;
- **частично**;
- **нет**.

Если нормы неизвестны, нельзя задним числом подставлять единую современную норму и выдавать результат как точное повторное заключение.

## 11. Что этот источник не даёт

Он не даёт сам набор reference values для каждого нерва.

Для этого следующий источник:

[[07 Научная база/План источников — экспертный пересмотр ЭНМГ#B5. Chen et al. 2016 — взрослые reference values|Chen et al. 2016]].

## 12. Минимальный вопрос будущего агента

Перед сравнением числа с нормой:

> эта норма получена и применена той же или достаточно сходной техникой?

Если ответ неизвестен, confidence понижается.
