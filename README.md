# vrl_get_logs

Репозиторий содержит скрипты для чтения и парсинга логов событий

- [get_syslog.toml](https://github.com/Anastasiia-Pov/vrl_get_logs/blob/main/get_syslog.toml) - скрипт для чтения логов системных событий, содержащих ошибку ("error"), и их последующей записи в JSON-файл;
- [get_authlogs.yaml](https://github.com/Anastasiia-Pov/vrl_get_logs/blob/main/get_authlogs.yaml) - скрипт для чтения логов об авторизации пользователей, и их последующей записи в JSON-файл;
- [modify_logs.yaml](https://github.com/Anastasiia-Pov/vrl_get_logs/blob/main/modify_logs.yaml) - скрипт для чтения логов об авторизации пользователей, фильтра "sudo/su" событий, добавления ключей "event_name" и "id" со значениями "AUTH" и значения в формате uuidv4, и их последующей записи в JSON-файл;
