

## Схема БД:



![](https://i.imgur.com/3oHRH3b.png)




```
<<<<<<< HEAD
Задание:Какие компании совершали перелеты на Boeing

=======
Задание: Вывести количество рейсов, совершенных на TU-134
>>>>>>> 908a29a132f9e7b9ad9c8654c1d6629957b163e6
```

```SQL
SELECT DISTINCT Company.name FROM Trip INNER JOIN Company on Trip.company = Company.id WHERE plane = "Boeing";
```

