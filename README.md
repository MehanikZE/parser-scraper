Для работы программы необходимо иметь установленную СУБД Postgresql По умолчанию настроено на следующие данные: DB_USER = "postgres" DB_NAME = "parser" DB_PASSWORD = "Vrt342zf" DB_HOST = "127.0.0.1" При использовании других учетных данных к БД, необходимо скорректировать их. Также необходимо наличие модулей из requirements.txt.  После запуска происходит сканирование страниц выборка данных  и последующее создание таблиц и наполнение их параметрами для дальнейшего взаимодествия с ними, если планируется перезапуск приложения то таблицы будут удалены , созданы и наполнены снова.