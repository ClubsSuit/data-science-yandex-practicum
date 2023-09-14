# Описание проекта

[ipynb](https://github.com/ClubsSuit/data-science-yandex-practicum/blob/main/10/texts.ipynb)

Необходимо обучить модель классифицировать комментарии на позитивные и негативные, на наборе данных с разметкой о токсичности комментариев. Метрика качества F1 должна быть не меньше 0.75. 

## Описание данных

* ```text``` - текст комментария
* ```toxic``` — целевой признак

## Используемые библиотеки

```Python```  ```Pandas```  ```NumPy```  ```sklearn```  ```spacy```  ```nltk```

## Выводы

Построены модели алгоритмов **LogisticRegression** и **SVC**. Метрики F1 этих моделей составили 0.76 и 0.74, соответственно.

В качестве финальной модели была выбрана модель с алгоритмом **LogisticRegression**, которая на тестовой выборке твитов, показала метрику F1 - 0.76.