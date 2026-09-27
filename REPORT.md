# Результаты лабораторной работы 1. Анализ публикаций arXiv по теме music

Источник данных: `arxiv_music_data.csv`, 1000 публикаций за 2021...2026 годы.

## EDA: распределение публикаций по годам и по длине текстов

![EDA](screenshots/cell_08_0.png)

## Закон Ципфа для слов корпуса

![Закон Ципфа](screenshots/zipf.png)

## Граф ключевых слов

![Граф ключевых слов](keyword_graph.png)

## Кластеры графа ключевых слов

![Кластеры](keyword_graph_clusters.png)

## Основные результаты ноутбука

```
Ключевых слов отобрано: 800 из 800

Топ 5 по Degree:
  music: 1.0000
  method: 0.9987
  model: 0.9987
  musical: 0.9987
  result: 0.9987
Топ 5 по Betweenness:
  online: 0.0055
  reading: 0.0038
  reasoning: 0.0032
  agent: 0.0029
  affective: 0.0027
Топ 5 по Eigenvector:
  music: 0.3165
  model: 0.2412
  musical: 0.1828
  generation: 0.1521
  method: 0.1400
Топ 5 по Closeness:
  music: 1.0000
  method: 0.9988
  model: 0.9988
  musical: 0.9988
  result: 0.9988

Граф публикаций: 1000 узлов, 498444 ребер
```