#Database abstraction library php mysqli

**Roadmap**
* Pdo?
* PhpUnit + Travis ?
* ����������� ������������ ���������� ��������
* ...
========

## �������������:
 ```php
      DB::connect('localhost', 'root', '', '<��� ��>'); - ������������ � ��
      DB::query('Select * From table;'); - ��������� ������ �� �������
      DB::getResult(); - ��������� ����������
      DB::close(); - ��������� ����������

      DB::insert('table_name', array('fields1'=>'values1'));
      DB::update('table_name', array('fields1'=>'values1'), array('fields1'=>'condition1'));
      DB::delete('table_name', array('fields'=>'condition'));
      DB::select('table_name', array(fields), [array('fields1'=>'condition1')]);
 ```
@author Sultanov Damir <damir.s94777@gmail.com>
@contributor Cherepanov Anton <davetoxa@gmail.com>