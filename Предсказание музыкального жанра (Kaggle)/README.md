# Модель для предсказания музыкальных жанров
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/Completed-ML-projects/blob/master/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BC%D1%83%D0%B7%D1%8B%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%B6%D0%B0%D0%BD%D1%80%D0%B0%20(Kaggle)/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%20%D0%BF%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B9%20%D0%B6%D0%B0%D0%BD%D1%80%D0%BE%D0%B2.ipynb)

[Ссылка на скрипт Pythone ML-модели](https://github.com/iashorokhov/Completed-ML-projects/blob/master/%D0%9F%D1%80%D0%B5%D0%B4%D1%81%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BC%D1%83%D0%B7%D1%8B%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%B6%D0%B0%D0%BD%D1%80%D0%B0%20(Kaggle)/%D0%9A%D0%BE%D0%B4%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8.py)

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
    
