# Предсказание температуры сплава
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/Completed-ML-projects/blob/master/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%86%D0%B5%D0%BD%D1%8B%20%D0%BD%D0%B0%20%D0%90%D0%B2%D1%82%D0%BE/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%86%D0%B5%D0%BD%D1%8B.ipynb) 
## Описание проекта:
Металлургический комбинат решил уменьшить потребление электроэнергии на этапе обработки стали. Для этого комбинату нужно контролировать температуру сплава. 
Требовалось создать модель, для предсказания температуры сплава с качеством MAE не выше 6.8
## Навыки и инструменты:
- Python
- SQL
- PostgreSQL
- Sqlalchemy
- Pandas
- Numpy
- Matplotlib
- GridSearchCV
- LGBMRegressor
- RandomForestRegressor
- Pipeline
- RobustScaler
- ColumnTransformer
- DummyRegressor
- Catboost
- Torch
## Общий вывод
Было проведено обучение нескольких моделей и по результатам тестирования лучшей выбрана модель градиентного бустинга LightGMB. Эта модель была протестирована на тестовом наборе данных и выбрана для передачи заказчикам.
