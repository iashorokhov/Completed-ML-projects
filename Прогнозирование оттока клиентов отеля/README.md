# Исследования для сети отелей 
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/Completed-ML-projects/blob/master/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%BE%D1%82%D0%B5%D0%BB%D1%8F/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0.ipynb)
## Описание проекта
Чтобы привлечь клиентов, сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты. Однако если клиент отменял бронирование, то компания терпела убытки. Сотрудники отеля могли, например, закупить продукты к приезду гостя или просто не успеть найти другого клиента. Чтобы решить эту проблему, нужно было разработать систему, которая предсказывает отказ от брони. Если модель покажет, что бронь будет отменена, то клиенту предлагается внести депозит. Размер депозита — 80% от стоимости номера за одни сутки и затрат на разовую уборку. Деньги будут списаны со счёта клиента, если он всё же отменит бронь.

## Навыки и инструменты
- Python
- Pandas
- Numpy
- Scipy
- sklearn.model_selection.train_test_split
- sklearn.model_selection.cross_val_score
- sklearn.model_selection.KFold
- sklearn.ensemble.RandomForestClassifier
- sklearn.metrics.mean_squared_error
- sklearn.metrics.recall_score
- sklearn.metrics.f1_score
- sklearn.metrics.roc_auc_score
- sklearn.metrics.roc_curve
- sklearn.metrics.accuracy_score
- Matplotlib
- sklearn.preprocessing.StandardScaler
- sklearn.preprocessing.OneHotEncoder
- sklearn.dummy.DummyClassifier
- imblearn.over_sampling.SMOTE

  ## Общий вывод
  Была проведена предобработка данных и EDA, посчитана прибыль отеля для дальнейшего сравнения целесообразности внедрения модели. Обучено несколько моделей, лучшей выбрана модель случайного леса, она же протестирована на тестовой выборке. По результатам подсчетов прибыль после внедрения модели станет значительно выше и полность окупит затраты на разработку. Также был составлен портрет ненадежного клиента для заказчика.
