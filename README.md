Role Name
=========

Роль для установки vector.

- Установка vector
- Запуск сервиса
- Интеграция vector с clickhouse

Requirements
------------

- clickhouse

Role Variables
--------------

Dependencies
------------

Хост clickhouse должен распологаться по адресу `192.168.10.3:8123`

Example Playbook
----------------

```yaml
hosts: vector
roles:
  - role: vector-role
```

License
-------

MIT

Author Information
------------------
