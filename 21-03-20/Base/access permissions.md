Все файлы имеют права доступа, которые хранятся в дескрипторе.

**u** - владелец
**g** - группа, в которую входит владелец
**o** - остальные

**r**, **w**, **x** - чтение, запись, выполнение
**s** - выполнение от имени владельца
**t** - запрет на удаление

Они отображаются при просмотре каталога, в котором зарегистрирован этот файл, в виде строки из 10 символов.

Первый символ - тип файла. (**дефис** - регулярный, **d** - каталог, **l** - мягкая ссылка, **b** - блочный спец., **c** - символьный спец.)

Далее идут три группы, состоящие из трех символов каждая: права владельца, группы пользователей, остальных пользователей.
В каждой группе символ - право чтения, записи и выполнения. Если **дефис** - право отключено.

Пример: ***-rw-r--r--*** 
Владелец имеет право читать и изменять файл, члены группы и остальные пользователи могут только читать файл.

#archived 