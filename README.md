Можно доработать следующими фитчами:
1. Добавить сервисы в переменную list_service, которые с помощью цикла {% for service in list_service %} балансировщик Nginx будет отрабатывать.
2. Можно добавить планировщик cronjob для автоматического обновления сертификатов
3. "Поиграться" c доступом к ресурсу по ip 
4. Добавить возможность ограничения доступа к сервису через клиентский сертификат.
 P.S. 
 Переменная client_max_body_size - для конфигурации Nginx, чтобы задать максимальный размер файла передаваемый клиентом (был опыт появления ошибок из-за большого размера файла)
 
 
