# Описание проекта

[ipynb](https://github.com/ClubsSuit/data-science-yandex-practicum/blob/main/07/gold-recovery.ipynb)

Необходимо подготовить прототип модели машинного обучения для золотодобывающего предприятия. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды, используя данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. Оценка качества модели по метрике sMAPE.

## Описание данных

Очистка золота происходит в три этапа:

флотация:

* первый этап очистки
* второй этап очистки

на каждом этапе данные, которые описывают технологический процесс разделены на 4 группы:

* входные параметры
* выходные параметры
* параметры очистной устанвки
* расчетные величины

## Использумые библиотеки

```Pandas```  ```Matplotlib```  ```NumPy```  ```Seaborn```

## Выводы

Построена модель ```RandomForestRegressor``` со следующими параметрами: 

* max_depth = 10
* n_estimators = 100

Тестирование модели на тестовых данных подтвердило адекватность модели
финальная sMAPE модели - **7,12**