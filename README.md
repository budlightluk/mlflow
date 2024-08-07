# Danila Ladygin budlighterluk@gmail.com @SkyWalker_OG

# Анализ пользовательского поведения на сайте интернет-магазина с использованием MLflow 💰

## Цель проекта

Построить модель, способную анализировать поведение пользователей на сайте интернет-магазина, с целью увеличения конверсии.

## Описание

Этот проект включает в себя:

- Генерацию синтетических данных логов пользователей
- Предварительную обработку данных
- Обучение модели для выявления аномалий в поведении пользователей
- Оценку производительности модели по метрикам Accuracy, Precision и Recall
- Логирование экспериментов с использованием MLflow
- Анализ данных и визуализацию

## Структура проекта

```plaintext
user_behavior_analysis/
│
├── data/
│   └── logs.csv  # Логи пользователей (необязательно, используется синтетический датасет)
│
├── notebooks/
│   └── user_behavior_analysis.ipynb  # Jupyter Notebook с реализацией проекта
│
├── requirements.txt  # Зависимости проекта
├── README.md  # Описание проекта
└── .gitignore  # Игнорируемые файлы и папки
