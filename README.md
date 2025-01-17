# tmdb_api
Упражнение на чтение кода. Фильмы с TMDB.

Данный проект позволяет скачать базу данных фильмов с `The Movie Data Base (TMDB)` и искать фильмы по этой базе. 

## .gitignore
Файл `.gitignore` содержит информацию для Git о том, какие файлы или папки проекта не следует добавлять в репозиторий.

## find_similar.py
Файл `find_similar.py` просит указать название локальной базы данных `MyFilmDB.json` и ввести название фильма для поиска фильмов, 
похожих по тематике по локальной базы.

Например, поиск фильмов, похожих на фильм Saw даст такой результат:

![find_similar](https://user-images.githubusercontent.com/37913906/142717466-95c63d32-70c5-4a00-b1fc-ba224e8528e7.png)

## hello_api_TMDB.py
Файл `hello_api_TMDB.py` показывает бюджет фильма:

![hello_api](https://user-images.githubusercontent.com/37913906/142717493-b9988105-9fae-4a40-bf35-7b21168d8305.png)

## LICENSE
Данный проект распространяется по свободной лицензии: кто угодно может свободно копировать, изменять, публиковать, использовать, 
компилировать, продавать или распространять ПО данного проекта.

Более подробная информация о правах на использование  ПО проекта представлен в файле `LICENSE`.

## make_own_db.py
Файл `make_own_db.py` позволяет создать локальную базу данных фильмов (файл `MyFilmDB.json`) в размере 1000 фильмов.

Процесс создания локальной БД может занять какое-то время, поэтому в начале программа выводит предупреждение:

![make_own_db](https://user-images.githubusercontent.com/37913906/142717499-37a39ca3-1f9e-4d22-82ed-97d2636498f8.png)

## own_db_helpers.py
Файл `own_db_helpers.py` загружает локальную базу данных фильмов в переменную `films_data`, к которой обращаются другие файлы проекта
при осуществлении поиска фильмов по локальной базе.

## requirements.txt
Файл `requirements.txt` опеределяет необходимые для проекта требования к зависимостям окружения.

## search_in_db.py
Файл `search_in_db.py` просит указать имя локальной базы данных `MyFilmDB.json` и ввести название фильма для осуществления по ней поиска, 
в которых встречается введённое название.

Например, поиск фильмов, с названием Rain даст такой результат:

![search_in_db_2](https://user-images.githubusercontent.com/37913906/142717503-a50e95e8-bb02-4ae3-838f-4dd084a96435.png)

## tmdb_helpers.py
Файл `tmdb_helpers.py` просит ввести ключ от базы данных `API TMDB v3` и формирует запрос к ней. 

Полученный ответ используется другими файлами проекта для работы с базой данных (её формирование, запрос доп.информации).

