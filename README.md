# lumbd
Предпочтительный тип записи данных - json.

Синтаксис:
~~~
lumbd path/to/empty/dir/bd tablename function arguments

lumbd . tablename createtable # Создаёт таблицу с указанным tablename

lumbd . tablename removetable # Удаляет таблицу

lumbd . tablename echo id # Выводит строку с указанным id

lumbd . tablename lastid # Выведет id последней записи по совместительство общее кол-во записей

lumbd . tablename lastrec #  Выведет последнюю запись

lumbd . tablename removestring id # Удаляет запись с указанным id

lumbd . tablename search prompt # Выводит строку/строки которые соответствуют указанному промпту стандартные регулярные выражения

lumbd . table name getstringid prompt # Выводит идентификаторы строк соответствующих промту 
~~~
