   ## Схема БД:



![](https://i.imgur.com/JNwmolM.png)




```
Задание: Выведите поля member_id, member_name и status из таблицы FamilyMembers.
```

```SQL
SELECT member_id, member_name,status FROM FamilyMembers

```

```
Задание: Выведите все столбцы из таблицы Payments.

```

```SQL
SELECT * FROM Payments

```

```
Задание:Выведите идентификаторы товаров (поле good) из таблицы Payments, стоимость которых больше 2000 единиц. Стоимость товара хранится в поле unit_price.
```

```SQL
Select good FROM Payments WHERE unit_price>2000

```
```
Задание:Выведите имена (поле member_name) членов семьи из таблицы FamilyMembers, чей статус (поле status) равен "father".
```

```SQL
SELECT member_name FROM FamilyMembers WHERE status IN ('father')

```
```
Задание:Выведите имя (поле member_name) и дату рождения (поле birthday) членов семьи из таблицы FamilyMembers, чей статус (поле status) равен "father" или "mother".
```

```SQL
SELECT  member_name,birthday FROM FamilyMembers WHERE status IN ('father','mother') 

```
```
Задание:Необходимо получить все комнаты, в которых есть как кухня (поле has_kitchen), так и интернет (поле has_internet). Напишите запрос, удовлетворяющий вышеописанному условию, который выводит все поля из таблицы Rooms.
Наличие обозначается 1 или true, а отсутствие 0 или false.
```

```SQL
SELECT *  FROM Rooms WHERE has_kitchen=true and has_internet=true

```
```
Задание:Выведите резервации комнат (поля room_id, start_date, end_date) из таблицы Reservations, у которых итоговая стоимость аренды (поле total) находится в промежутке от 500 до 1200 включительно.
```

```SQL
SELECT room_id, start_date, end_date FROM Reservations WHERE total BETWEEN 500 AND 1200 ;

```
```
Задание:Для каждого отдельного платежа выведите идентификатор товара и сумму, потраченную на него, в отсортированном по убыванию этой суммы виде. Список платежей находится в таблице Payments.
Для вывода суммы используйте псевдоним sum.
```

```SQL


```
```
Задание:
```

```SQL


```

