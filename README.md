# Простое веб-окружение (nginx + apache + mysql + php + phpmyadmin)

Простенькое веб-окружение для запуска в docker. В качестве СУБД используется MariaDB.

### Версия PHP
`7.4`

### Варианта запуска PHP
1. nginx + apache + mod_php
2. nginx + apache + php-fpm

### Запуск
`docker-compose up`

### Порты
`8081` - веб-сервер
`8082` - phpmyadmin

### MySQL
`root` - логин
`root` - пароль