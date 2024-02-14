# Алгоритм для подбора наболее похожих товаров из набора данных
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/portfolio/blob/master/Items-matching-algorithm-Workshop--main/items-matching.ipynb)
## Описание проекта
Необходимо было разработать алгоритм подбора наиболее подходящих товаров для выборки validation из датасета base и протестировать алгоритм с помощью метрики accuracy@5
## Навыки и инструменты
- Python
- Pandas
- Numpy
- sklearn.preprocessing.StandardScaler
- Faiss
## Общий вывод
В качестве основного алгоритма для поиска ближайших соседей была выбрана библиотека Faiss. Обучение происходило на выборке из общих данных. По результатам тестирований метрика accuracy@5 достигла 63.4. Результат устроил заказчика и был передан ему. 
