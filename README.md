# Пакет для работы с базой данных
## Использование
``use rsgrinko\DB;``

``$db = new DB('db_server', 'db_user', 'db_pass', 'db_name');``

``$res = $db->query('select * from logs limit 100');``

## Все методы можно посмотреть в классе DB
