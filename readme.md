# Преддипломная практика на тему "Анализ схожести научных текстов с помощью методов естественной обработки языка и машинного обучения"
Структура проекта:
│PDipPraktika
├── /russian-scientific-articles    # Первоначальный датасет Kaggle https://www.kaggle.com/datasets/ergkerg/russian-scientific-articles/data
├── /data                           # Собранный датасет из .txt
│   └── df.parquet
├── /models                         # Сохраненные обученные модели .pt
│   └──cosine_mlp.pt
│   └── pair_mlp.pt
├── /reports                        # Результат выполнения
│   └── comparison_report.txt       # Отчёт по сравнению текстов
├── nlp_ml_similarity.ipynb         # Рабочий Jupyter Notebook
├── readme.md                       # Документация проекта
├── requirements.txt                # Python-зависимости
├── tfidf_vectorizer.joblib         # Сохраненный векторизатор текста
