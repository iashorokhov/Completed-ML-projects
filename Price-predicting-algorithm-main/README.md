# Алгоритм, определяющий цену на автомобиль
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/portfolio/blob/master/Price-predicting-algorithm-main/price-gbm-ml.ipynb) 
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
