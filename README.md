# Chronosphere Model Verification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Chronosphere-theory/void/blob/main/notebooks/chronosphere_verification.ipynb)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18844784.svg)](https://doi.org/10.5281/zenodo.18844784)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

## 📌 Описание

Этот репозиторий содержит код для проверки **модели Хроносферы** и 3D визуализацию полученных результатов — дискретной модели пространства-времени с динамической границей. Код выполняет:

- MCMC анализ с использованием данных DESI DR1, Cosmicflows-4, Pantheon+ и SH0ES
- Сравнение с ΛCDM моделью
- Визуализацию результатов

### Ключевые результаты MCMC анализа

| Параметр | Значение | Теоретическое | Согласие |
|----------|----------|---------------|----------|
| **β** | 0.01126 ± 0.00145 | (π-3)/(4π) = 0.01127 | **0.0σ** |
| **R_void** | 798 ± 2 Мпк | — | — |
| **v_max** | 194 ± 37 км/с | — | — |
| **Ω_m** | 0.250 ± 0.000 | 0.315 | — |
| **ΔAIC** | -5241 | — | предпочтительнее ΛCDM |

---

## 🚀 Быстрый старт

### Запуск в Google Colab (рекомендуется)

1. Нажмите на значок **Open In Colab** выше
2. Выполните ячейки последовательно (Shift+Enter)
3. Через 10-15 минут вы получите результаты

📄 Лицензия
Все материалы распространяются под лицензией CC0 1.0 Universal.

📧 Контакты
Автор: А.Ю. Огородников
Email: artemogorodnikov@cyandex.ru
GitHub: @Chronosphere-theory
