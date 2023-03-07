# D-7.5-News-Portal-

для Windows

Первый терминал: celery -A News worker -l INFO --concurrency 1 -P solo

Второй терминал: celery -A News beat -l INFO

для запуска celery -A News worker -l INFO
