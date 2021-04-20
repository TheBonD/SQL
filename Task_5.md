

## Схема БД:



![](https://i.imgur.com/3oHRH3b.png)




```
Задание:Вывести количество рейсов, совершенных на TU-134
```

```SQL
SELECT COUNT(plane) as count FROM Trip WHERE plane = "TU-134"
```

