Имя роли
=========

## base-package-install - роль для установки базовых и специфичных пакетов на хосты!

Требования
------------

Работоспособность проекта проверена на ansible v2.20

Переменные роли
--------------

* **base_package_install__default_packages** - здесь указаны базовые пакеты
* **base_package_install__specific_packages** - нужно указать в group_vars или конкретному хосту свой перечень специфичных пакетов

Пример плейбука
----------------

```
- hosts: all
  roles: base-package-install
```

Информация об авторе
------------------

Kiselev Mikhail (duranvoin)
