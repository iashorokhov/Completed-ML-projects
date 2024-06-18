# Поиск изображений по текстовому запросу
[Ссылка на Jupyter Notebook](https://github.com/iashorokhov/Completed-ML-projects/blob/master/%D0%9F%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%BE%D1%82%D0%B5%D0%BB%D1%8F/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BD%D0%BE%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20%D0%BE%D1%82%D1%82%D0%BE%D0%BA%D0%B0.ipynb)
## Описание проекта
Для сервиса фотографий необходимо было разработать демонстрационную версию поиска изображений по запросу.
Для демонстрационной версии нужно было обучить модель, которая получит векторное представление изображения, векторное представление текста, а на выходе выдаст число от 0 до 1 — покажет, насколько текст и картинка подходят друг другу.

## Навыки и инструменты
- Python
- Pandas
- Numpy
- Matplotlib
- WordCloud
- torchvision
- torch
- PIL
- GroupShuffleSplit
- DummyRegressor
- LinearRegression
- Ridge
- CLIPModel
- CLIPProcessor

  ## Общий вывод
  Были протестированы несколько моделей, включая самописную нейросеть и модель CLip от OpenAI. В качестве лучшей модели выбрана CLIP и она же рекомендована к использованию заказчику.
