# laravel8-timeweb-demo - Демонстрационный проект для быстрого деплоя на Timeweb apps 

## Для локальной разработки

Обртатите внимание, что данный пример работает с sqlite3, поэтому в примере мы сразу разместили пустую бд по следующему адресу:
```bash
./database/database.sqlite
```

__ВАЖНО!__ Если ваша БД содержит важные данные не допускайте ее попадания в github, или используйте MYSQL. Данный пример просто оптимизирован для знакомства с размещением на платформе Timeweb Apps.

Сначала выполните миграцию
```bash
php artisan migrate
```

Затем, выполните команду (для заполнения таблиц `users` и `news`) тестовыми данными:
```bash
php artisan db:seed
```

Далее запускайте проект
```bash
php artisan serve
```