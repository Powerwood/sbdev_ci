sbdev_ci
========

Torrent indexing on Codeigniter


У движка пока что нет инстолятора но уверяю что руками установить движок будет по силу даже не "гуру" :)

1. CHMOD 777 папку (/public/upload/torrents) (/public/upload/avatars) (/application/cache)

2. создаём базу данных (обычно это делаем с помощью 'phpmyadmin')

3. редактируем файл базы данных (/applications/config/database.php)

4. заливаем файл (database.sql) в базу которую вы создали в 2. пункте. Файл находиться в корневой
папке движка (там же где 'index.php')

5. редактируем файл конфигураций (/applications/config/config.php)

6. Логин: admin Пароль: password

7. Готово!
