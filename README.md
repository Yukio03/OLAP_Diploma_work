<h1 align="center"> Разработка OLAP-куба для анализа данных </h1>


*Структура проекта:*
<ul>
  <li>data/ - содержит файлы с данными для загрузки в хранилище</li>
  <li>code/ - содержит файлы исходного кода разработки</li>
  <ul>
  <li>ExcelToMSSQL.ipynb - файл с исходным кодом ETL-процесса</li>
  <li>CodeSQL.txt - файл с кодом создания БД и таблиц в MSSQL
  </ul>
  <li>report/ - содержит отчеты SSRS из OLAP куба</li>
</ul>

____

## Исходные данные

Данные представлены в виде Excel файла, в котором структурированы по столбцам.
![image](https://user-images.githubusercontent.com/86725214/232725913-408d6d7b-c0ef-4a53-a88d-8ccd5f636c10.png)



## *Задача*:

Разработать хранилище данных на основе которого будет формироваться OLAP-куб для анализа.


## Даталогическая модель ХД

![image](https://user-images.githubusercontent.com/86725214/232725316-155d9f12-4d58-4df3-80ef-4da63d634b47.png)



