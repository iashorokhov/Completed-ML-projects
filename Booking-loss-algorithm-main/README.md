# Исследования для сети отелей «Как в гостях». 
[Ссылка на Hupyter Notebook](https://github.com/iashorokhov/portfolio/blob/master/Booking-loss-algorithm-main/project-1.ipynb)
## Описание проекта
Чтобы привлечь клиентов, эта сеть отелей добавила на свой сайт возможность забронировать номер без предоплаты. Однако если клиент отменял бронирование, то компания терпела убытки. Сотрудники отеля могли, например, закупить продукты к приезду гостя или просто не успеть найти другого клиента. Чтобы решить эту проблему, нужно было разработать систему, которая предсказывает отказ от брони. Если модель покажет, что бронь будет отменена, то клиенту предлагается внести депозит. Размер депозита — 80% от стоимости номера за одни сутки и затрат на разовую уборку. Деньги будут списаны со счёта клиента, если он всё же отменит бронь.

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
