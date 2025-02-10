Модуль 1: Введение в Microsoft SQL Server

Лабораторная работа: Работа с инструментами SQL Server

Упражнение 1: Работа с SQL Server Management Studio
```
Задача 1: Открытие Microsoft SQL Server Management Studio

1. Убедитесь, что виртуальные машины  20761C-MIA-DC и 20761C-MIA-SQL
запущены.
2. Войдите в 20761C-MIA-SQL как ADVENTUREWORKS\Student с паролем Pa55w.rd.
3. Запустите SQL Server Management Studio.
4. В диалоговом окне «Подключение к серверу» нажмите «Отмена».
5. Закройте окно обозревателя объектов, нажав значок «Закрыть».
6. Закройте окно обозревателя решений, нажав значок «Закрыть».
7. Чтобы открыть панель обозревателя объектов, в меню «Вид» выберите «Обозреватель объектов» (или нажмите клавишу F8).
8. Чтобы открыть панель Solution Explorer, в меню View выберите Solution Explorer (или нажмите Ctrl+Alt+L).

Задача 2: настройка параметров редактора

1. В SQL Server Management Studio в меню Tools выберите Options.
2. В диалоговом окне Options разверните параметр Environment и выберите Fonts and Colors.
3. В списке Show settings for выберите Text Editor.
4. В поле Size установите размер шрифта 14.
5. В левой панели разверните Text Editor, разверните Transact-SQL и щелкните IntelliSense.
6. В разделе Transact-SQL IntelliSense Settings снимите флажок Enable IntelliSense.
7. В левой панели в разделе Transact-SQL щелкните Tabs и измените размер Tab на 6.
8. В левой панели разверните Query Results, разверните SQL Server и щелкните Results to Grid.
9. Установите флажок Включать заголовки столбцов при копировании или сохранении результатов, а затем нажмите
ОК.
```

Упражнение 2: Создание и организация скриптов T-SQL
```
Задание 1: Создание проекта

1. В меню Файл выберите Новый, а затем нажмите Проект.
2. В диалоговом окне Новый проект нажмите Скрипты SQL Server.
3. В поле Имя введите MyFirstProject.
4. В поле Расположение введите D:\Labfiles\Lab01\Starter, а затем нажмите ОК, чтобы создать новый проект.
5. В обозревателе решений в разделе MyFirstProject щелкните правой кнопкой мыши папку Запросы и выберите Новый запрос.
6. В диалоговом окне Подключение к ядру базы данных нажмите Отмена.
7. В папке Queries щелкните правой кнопкой мыши SQLQuery1.sql, щелкните Rename, введите MyFirstQueryFile и
нажмите Enter.
8. В меню File щелкните Save All.

Задача 2: Добавить дополнительный файл запроса
1. В Solution Explorer щелкните правой кнопкой мыши папку Queries и выберите New Query.
2. В диалоговом окне Connect to Database Engine щелкните Cancel.
3. В папке Queries щелкните правой кнопкой мыши SQLQuery1.sql, щелкните Rename, введите MySecondQueryFile и
нажмите Enter.
4. На панели задач щелкните File Explorer.
5. В File Explorer перейдите в папку D:\Labfiles\Lab01\Starter\MyFirstProject\MyFirstProject,
чтобы увидеть, где были созданы файлы.
6. В SQL Server Management Studio в обозревателе решений щелкните правой кнопкой мыши MySecondQueryFile.sql,
а затем щелкните Remove.
7. В диалоговом окне Microsoft SQL Server Management Studio щелкните Remove.
8. В проводнике файлов нажмите F5 для обновления, обратите внимание, что файл MySecondQueryFile.sql все еще там.
9. В решении SQL Server Management Studio в обозревателе решений щелкните правой кнопкой мыши MyFirstQueryFile.sql,
а затем щелкните Remove.
10. В диалоговом окне Microsoft SQL Server Management Studio щелкните Delete.
11. В проводнике файлов нажмите F5 для обновления, обратите внимание, что файл MyFirstQueryFile.sql был удален.

Задача 3: повторное открытие созданного проекта
1. В решении SQL Server Management Studio в меню File выберите Save All.
2. В меню File выберите Exit, чтобы закрыть проект и SQL Server Management Studio.
3. Откройте SQL Server Management Studio.
4. В диалоговом окне «Подключение к серверу» нажмите «Отмена».
5. В меню «Файл» выберите «Открыть», а затем нажмите «Проект/решение».
6. В диалоговом окне «Открыть проект» перейдите в папку D:\Labfiles\Lab01\Starter\MyFirstProject»,
нажмите MyFirstProject.ssmssln и нажмите «Открыть».
7. В проводнике перейдите в папку D:\Labfiles\Lab01\Starter\MyFirstProject\MyFirstProject.
8. Перетащите файл MySecondQueryFile.sql в папку «Запросы» в обозревателе решений. 
9. В меню «Файл» нажмите «Сохранить все».
```
