# Описание проекта

[ipynb](https://github.com/ClubsSuit/data-science-yandex-practicum/blob/main/11/pictures.ipynb)

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:

* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
* Контролировать добросовестность кассиров при продаже алкоголя.

Для этого обучим модель на датасете, который содержит набор фотографий лиц людей и их возраст. 

Нейронная сеть должна иметь метрику MAE меньше 8 лет.

# Описание данных

* ```file_name``` - адресс хранения файла с фотографией
* ```real_age``` - настоящий возраст

## Используемые библиотеки

```Python```  ```Pandas```  ```NumPy```  ```Keras```  ```TensorFlow```  ```ResNet50```

## Выводы

Для построения модели использовалась сеть ResNet50 c финальными слоями пулинга, слоя с 64 нейронами и финального слоя с одним нейроном. Обученная модель продемонстрировала не плохие результаты оценки возраста людей по фотографии. Тестовое MAE составило 7.2 года.