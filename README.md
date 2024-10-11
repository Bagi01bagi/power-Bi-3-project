Источник данных OData Feed
https://services.odata.org/V3/Northwind/Northwind.svc/
Загружаем таблицы и создаем между ними связи:

Orders
Order_details
Products
Categories
Suppliers

Создаем календарь с полями (Можно скопировать из предыдущих заданий)

"Date"
"Year"
"MonthNumber"
"MonthName"
"WeekNum"
"DayName"
"DayInMonth"

Создаем связь Orders->OrderDate - DimDates->Date
Создаем меру Amount, которая считает сумму выручки. По таблице Order_details вычисляем сумму выражения 'Order_Details'[Quantity] * 'Order_Details'[UnitPrice].

Создаем заголовок вверху
1.Добавляем логотип любой компании в левом верхнем углу
2.Слева добавляем 3 среза: По стране доставки, Категории продукта, Региону поставщика
3.Под заголовком отображаем 3 карточки: с выручкой, количеством проданных штук товара, средней ценой продажи одной штуки товара
4.Добавляем точечную диаграмму, на которой отобразим зависимость количество проданных штук товара от средней цены продажи за одну штуку. На каждый товар отображаем одну точку. 
5.Делаем 2 кнопки: "Гистограмма" и "Круговая диаграмма". 
6.В зависимости от того какая из кнопок нажата - отображаем или гистограмму или круговую диаграмму с выручкой по категориям продуктов.
7.Делаем фон у всего отчета.
КАК СКАЗАЛИ ТАК И СДЕЛАЛА

![3project](https://github.com/Bagi01bagi/power-Bi-3-project/blob/main/Безымянный.png)
