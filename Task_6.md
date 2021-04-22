

## Схема БД:



![](https://i.imgur.com/3oHRH3b.png)




```
Какие компании совершали перелеты на Boeing.
```

```SQL
SELECT DISTINCT Company.name FROM Trip INNER JOIN Company on Trip.company = Company.id WHERE plane = "Boeing";
```

