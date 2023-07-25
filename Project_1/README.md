
# <center> Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта]()
2. [Описание данных]()
3. [Зависимости]()
4. [Установка проекта]()
5. [Использование проекта]()
6. [Выводы]()

## Описание проекта

**Цель анализа данных** — преобразование, исследование и очистка данных перед построением модели для компании *HeadHunter*. Данную модель компания хочет использовать для автоматического определения примерного уровня заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Во многих задачах анализ и очистка данных — это самая главная часть этапа подготовки данных к построению модели, которая нередко занимает большую часть времени работы над задачей.

Основные этапы анализа данных:
* Базовый анализ структуры данных.
* Преобразование данных.
* Разведывательный анализ.
* Очистка данных.

**О структуре проекта:**
* [data]() - папка с исходными табличными данными
* [plotly]() - папка с графиками, необходимыми для проекта
* [Project-1._data_analysis.ipynb]() - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задач анализа и очистки данных


## Описание данных
В этом проекте используются база данных с резюме, выгруженная с сайта поиска вакансий *hh.ru* [dst-3.0_16_1_hh_database.csv]() и данные о курсе валют за период с 29.12.2017 по 05.12.2019 годы [ExchangeRates.csv]().

Исходный датасет представляет собой набор данных из таблицы с информацией о соискателях вакансий на сайте компании *HeadHunter*, а также таблица, в которой содержится информация о курсе валют за период с 29.12.2017 по 05.12.2019 годы.

## Используемые зависимости
* Python (3.11.4):
    * [numpy (1.25.1)]()
    * [pandas (2.0.3)]()
    * [matplotlib (3.7.2)]()
    * [seaborn (0.12.2)]()
    * [plotly (5.15.0)]()

## Установка проекта


## Использование
Вся информация о работе представлена в jupyter-ноутбуке Project-1._data_analysis.ipynb.

## Выводы

В данной работе, с помощью анализа данных удалось выявить выбросы и очистить от них датасет. Также некоторые данные были преобразованы для более удобной работы с ними. Теперь датасет готов к дальнейшей обработке и построению модели. 