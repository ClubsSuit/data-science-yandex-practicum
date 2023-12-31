# Описание проекта

[ipynb](https://github.com/ClubsSuit/data-science-yandex-practicum/blob/main/04/tarifs.ipynb)

Проект системы анализа поведения клиентов и предложения пользователям нового тарифа связи. По данным о поведении клиентов, которые уже перешли на эти тарифы, нужно построить модель для задачи классификации, которая выберет подходящий тариф. 

## Описание данных

* ```сalls``` — количество звонков
* ```minutes``` — суммарная длительность звонков в минутах
* ```messages``` — количество sms-сообщений
* ```mb_used``` — израсходованный интернет-трафик в Мб
* ```is_ultra``` — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0)

## Используемые библиотеки

```Pandas```  ```Matplotlib```  ```NumPy```  ```Seaborn```

## Выводы

Построена модель "Решающего Древа" с accuracy - 0,78 на тестовой выборке.
