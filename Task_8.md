

## Схема БД:



![](https://i.imgur.com/3oHRH3b.png)




```
Какие компании организуют перелеты с Владивостока (Vladivostok)?
Поля в результирующей таблице:name
```

```SQL
SELECT DISTINCT  Company.name FROM Trip INNER JOIN Company ON Trip.company=Company.id WHERE town_from = 'Vladivostok'  
```

