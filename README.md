#Database abstraction library php mysqli

**Roadmap**
* Pdo?
* PhpUnit + Travis ?
* Обеспечение безопасности выполнения запросов
* ...
========

## Использование:
 ```php
      DB::connect('localhost', 'root', '', '<имя БД>'); - подключаемся к БД
      DB::query('Select * From table;'); - выполняем запрос на выборку
      DB::getResult(); - получение результата
      DB::close(); - закрываем соединение

      DB::insert('table_name', array('fields1'=>'values1'));
      DB::update('table_name', array('fields1'=>'values1'), array('fields1'=>'condition1'));
      DB::delete('table_name', array('fields'=>'condition'));
      DB::select('table_name', array(fields), [array('fields1'=>'condition1')]);
 ```
@author Sultanov Damir <damir.s94777@gmail.com>
@contributor Cherepanov Anton <davetoxa@gmail.com>