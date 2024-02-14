# Модель для предсказания музыкальных жанров
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/portfolio/blob/master/ML-model-predicting-music-genre-Kaggle--main/project_notebook.ipynb)

[Ссылка на скрипт Pythone ML-модели](https://github.com/iashorokhov/portfolio/blob/master/ML-model-predicting-music-genre-Kaggle--main/rf_model.py)

## Описание проекта
Стриминговый сервис расширяет работу с новыми артистами и музыкантами, в связи с чем возникла задача -- правильно классифицировать новые музыкальные треки, чтобы улучшить работу рекомендательной системы. Коллеги из отдела работы со звуком подготовили датасет, в котором собраны некоторые характеристики музыкальных произведений и их жанры. Задача - разработать модель, позволяющую классифицировать музыкальные произведения по жанрам.
## Навыки и инструменты
- Python
- Pandas
- Numpy
- Matplotlib
- Scipy
- sklearn.pipeline
- sklearn.metrics.mean_absolute_error
- sklearn.feature_extraction.text.TfidfVectorizer
- sklearn.ensemble.RandomForestClassifier
- Catboost.CatBoostClassifier
- sklearn.compose.ColumnTransformer
- imblearn.over_sampling.SMOTE
- sklearn.preprocessing.LabelEncoder
- sklearn.preprocessing.StandardScaler
- sklearn.preprocessing.OneHotEncoder

## Общий вывод
Проведен полноценны EDA и первичная обработка данных. Протестированы две модели, одна из которых градиентный бустинг CatboostClassifier. По итогам тестирования лучшей выбрана модель случайного леса. Она же использовалась для сбора предсказаний на тестовой выборке, которая была передана для оценки на соревновании [Соревнование Kaggle](https://www.kaggle.com/competitions/music-genre-prediction-m125ds)
    
