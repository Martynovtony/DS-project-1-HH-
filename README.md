# <center> PROJECT-1. Анализ вакансий hh.ru на Python </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)


## Описание проекта

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.

Проект состоит из четырех частей:

* Базовый анализ структуры данных.
* Преобразование данных.
* Разведывательный анализ.
* Очистка данных.

Цель предобработки данных — избавиться от «мусора», который может помешать моделированию или исказить его результаты. Заполнить пропущенные значения. Удалить малоинформативные признаки и значения.

Данный проект направлен на тренировку навыков применения различных методов предобработки данных на каждом из этапов Feature Engineering на примере датасета резюме с сайта HeadHunter.


**О структуре проекта:**
* [data](./data) - папка с исходными табличными данными (в т.ч. курс валют)
* [html](./html) - папка с изображениями(визуализация), необходимыми для проекта 
* [Project-1.HH](./Project-1.HH.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задач анализа данных


## Описание данных
В нашем распоряжении [датасет](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?pli=1) с данными резюме, выгруженными с сайта поиска вакансий hh.ru. **Сохраните файл в папку data, чтобы корректно воспроизвести код.**
 

## Используемые зависимости
* Python (3.12.6):
    * [numpy (2.1.2)](https://numpy.org)
    * [pandas (2.2.3)](https://pandas.pydata.org)
    * [matplotlib (3.9.4)](https://matplotlib.org)
    * [seaborn (0.13.2)](https://seaborn.pydata.org)
    * [plotly.express (5.24.1)](https://plotly.com/python/plotly-express/)
* Для воспроизведения кода можно воспользоваться файлом [requirements](./requirements.txt)

## Установка проекта

```
git clone https://github.com/Martynovtony/DS-project-1-HH
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке [Project-1.HH](./Project-1.HH.ipynb).

## Авторы

* Антон Мартынов

## Выводы
В результате проделанной работы удалось выполнить все поставленные задачи:
- Преобразование данных (создание полезных признаков, обработка пропусков)
- Очистка данных (удаление неинформативных признаков и значений)
- Визуализация данных (выявление зависимостей в данных, вывод информации с помощью графиков и диаграмм).