

## Схема БД:



![](https://i.imgur.com/3oHRH3b.png)




```
Вывести все названия самолётов, на которых можно улететь в Москву (Moscow)
Поля в результирующей таблице:plane
```

```SQL
SELECT DISTINCT plane from Trip WHERE town_to Like '%Moscow'
```

