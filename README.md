###  С помощью pandahouse выгрузим нужные данные из ClickHouse и проанализируем их в python. 

Дан датасет, содержащий информацию об объявлениях на Airbnb в Лондоне. Необходимо выполнить задания:

- Выгрузите из таблицы данные о цене в зависимости от типа жилья.Сгруппируйте полученный датафрейм по типу жилья и посчитайте 75-й перцентиль цены.
- К данным о цене и типе комнаты дополнительно выгрузите данные о рейтинге жилья (review_scores_rating).Постройте график рассеивания, который покажет зависимость средней оценки от средней цены по типу жилья.
- Проверьте, какие способы верификации аккаунта использовали хозяева, предлагающие различные впечатления. 
- Посмотрите, для скольких объявлений и в каких районах хозяева указали впечатления. Постройте heatmap.
- Выгрузите данные о ценах за ночь для разных типов жилья, для которых также доступен какой-либо вид впечатления и построить два графика, используя distplot из библиотеки seaborn.
- Выгрузите данные о цене, типе жилья и дате первого отзыва, начиная со 2 января 2010 года. Используя библиотеку seaborn и функцию lineplot, постройте график динамики средних цен на жилье в зависимости от типа комнаты по годам (ось X).
