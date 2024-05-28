# Алгоритм, определяющий цену на автомобиль
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/Completed-ML-projects/blob/master/%D0%9E%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%86%D0%B5%D0%BD%D1%8B%20%D0%BD%D0%B0%20%D0%90%D0%B2%D1%82%D0%BE/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%20%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F%20%D1%86%D0%B5%D0%BD%D1%8B.ipynb) 
## Описание проекта:
С помощью исторических данных (технические характеристики, комплектации и цены автомобилей),  нужно было построить модель, которая сможет определять рыночную смтоимость автомобиля с качеством RMSE не более 2500.
## Навыки и инструменты:
- Python
- Pandas
- Numpy
- Matplotlib
- sklearn.model_selection.GridSearchCV
- sklearn.model_selection.train_test_split
- sklearn.metrics.make_scorer
- sklearn.metrics.mean_squared_error
- lightgbm.LGBMRegressor
- sklearn.ensemble.RandomForestRegressor
- sklearn.pipeline.Pipeline
- sklearn.preprocessing.StandardScaler
- sklearn.preprocessing.OneHotEncoder
- sklearn.compose.ColumnTransformer
- sklearn.dummy.DummyRegressor

## Общий вывод
Было проведено обучение выбранных моделей и по результатам тестирования лучшей выбрана модель градиентного бустинга LightGMB. Эта модель была протестирована на тестовом наборе данных и выбрана для передачи заказчикам.
