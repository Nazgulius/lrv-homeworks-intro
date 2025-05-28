#  Домашнее задание к занятию «1.1. Введение в Laravel.»

## Задание 3. Установка Laravel  

Вопросы:  
- Перечислите список composer-пакетов, которые использует фреймворк Laravel после установки.  
  Ответ:  
  "require": {  
    "php": "^8.2",  
    "laravel/framework": "^12.0",  
    "laravel/tinker": "^2.10.1"  
  },  
  "require-dev": {  
    "fakerphp/faker": "^1.23",  
    "laravel/pail": "^1.2.2",  
    "laravel/pint": "^1.13",  
    "laravel/sail": "^1.41",  
    "mockery/mockery": "^1.6",  
    "nunomaduro/collision": "^8.6",  
    "phpunit/phpunit": "^11.5.3"  
  },  
  
- Изучите директорию config и опишите какие файлы хранятся в этой директории.  
  Ответ:  В config находятся конфигурационные файлы приложения. А именно: app.php, auth.php, cache.php, database.php, filesystems.php, logging.php, mail.php, queue.php, services.php, session.php.
     
- В какой директории хранятся основные файлы (классы) с бизнес-логикой приложения?  
  Ответ:  директория "add".  
