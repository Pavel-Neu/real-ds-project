
# <center> Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Описание-проекта)
2. [Описание данных](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Описание-данных)
3. [Используемые зависимости](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Используемые-зависимости)
4. [Установка проекта](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Установка-проекта)
5. [Использование проекта](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Использование-проекта)
6. [Выводы](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Выводы)

## Описание проекта

**Цель анализа данных** — преобразование, исследование и очистка данных перед построением модели для компании *HeadHunter*. Данную модель компания хочет использовать для автоматического определения примерного уровня заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Во многих задачах анализ и очистка данных — это самая главная часть этапа подготовки данных к построению модели, которая нередко занимает большую часть времени работы над задачей.

Основные этапы анализа данных:
* Базовый анализ структуры данных.
* Преобразование данных.
* Разведывательный анализ.
* Очистка данных.

**О структуре проекта:**
* [data](./data) - папка с исходными табличными данными
* [plotly](./plotly) - папка с графиками, необходимыми для проекта
* [Project-1._data_analysis.ipynb](./Project-1._data_analysis.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задач анализа и очистки данных

:arrow_up:[к оглавлению](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Оглавление)

## Описание данных
В этом проекте используются база данных с резюме, выгруженная с сайта поиска вакансий *hh.ru* [dst-3.0_16_1_hh_database.csv](https://drive.google.com/file/d/1se0EGX43NrOCXuW8ZCGjgrTeWVc6BwBs/view?usp=sharing) и данные о курсе валют за период с 29.12.2017 по 05.12.2019 годы [ExchangeRates.csv](https://drive.google.com/file/d/1Y72jHgpPvT2O9EK5TwziG4Arp6jqfJDD/view?usp=sharing).

Исходный датасет представляет собой набор данных из таблицы с информацией о соискателях вакансий на сайте компании *HeadHunter*, а также таблица, в которой содержится информация о курсе валют за период с 29.12.2017 по 05.12.2019 годы.

:arrow_up:[к оглавлению](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Оглавление)

## Используемые зависимости
* Python (3.11.4):
    * [numpy (1.25.1)](https://numpy.org)
    * [pandas (2.0.3)](https://pandas.pydata.org)
    * [matplotlib (3.7.2)](https://matplotlib.org)
    * [seaborn (0.12.2)](https://seaborn.pydata.org)
    * [plotly (5.15.0)](https://plotly.com/python/)

:arrow_up:[к оглавлению](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Оглавление)

## Установка проекта

```
git clone https://github.com/Pavel-Neu/real-ds-project.git
```

:arrow_up:[к оглавлению](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Оглавление)

## Использование проекта
Вся информация о работе представлена в jupyter-ноутбуке Project-1._data_analysis.ipynb.

:arrow_up:[к оглавлению](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Оглавление)

## Выводы
В данной работе, с помощью анализа данных удалось выявить выбросы, дубликаты и очистить от них датасет. Также некоторые данные были преобразованы для более удобной работы с ними, а пустые значения были заменены медианным. Теперь датасет готов к дальнейшей обработке и построению модели. 

:arrow_up:[к оглавлению](https://github.com/Pavel-Neu/real-ds-project/blob/master/README.md#Оглавление)