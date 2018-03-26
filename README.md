# Карта России в SVG

## Описание

Простенькая библиотека для рисования у правления картой Российской Федерации в SVG. Работает на основе библиотеки RaphaelJS.
За рендер карты отвечает скрипт [russian-map.js](https://github.com/kalyabin/russian-map/blob/master/russian-map.js).

Название библиотеки взято "с потолка", поэтому теоретически этот скрипт может заниматься отрисовкой любой карты, либой страны, любого региона или города.

## Откуда берутся координаты границ

Изначально координаты границ были взяты с какого-то сайта, предположительно, из Wikipedia. После этого координаты неоднократно модифицировались.

Координаты для SVG и параметры отображения SVG-элемента берутся:

* для регионов - файл [with-regions.json](https://github.com/kalyabin/russian-map/blob/master/with-regions.json)
* для федеральных округов - файл [with-districts.json](https://github.com/kalyabin/russian-map/blob/master/with-districts.json)

## Примеры

Пример рендера карты с субъектами Российской Федерации приведён в файле [with-regions.html](https://github.com/kalyabin/russian-map/blob/master/with-regions.html).
Пример рендера карты с федеральными округами Российской Федерации приведён в файле [with-districts.html](https://github.com/kalyabin/russian-map/blob/master/with-districts.html).

## TODO

+ отказаться от устаревшего Raphael.js (1.5) и написать под новую 2-ю версию.
