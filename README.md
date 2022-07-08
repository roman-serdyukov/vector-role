Vector-role
=========

Роль для установки и настройки Vector.
Скачивает с сайта пакет, устанавливает и проводит валидацию настроек.

Requirements
------------

Протестировано на работоспособность в Ubuntu 20.04 и Centos 7.

Role Variables
--------------
- Возможно изменить версию пакета
```
vector_version:
```
- Настройки можно менять в файле vector.toml.j2

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector, when: ansible_system == 'Linux' }

License
-------

MIT

Author Information
------------------

Сердюков Роман
reserdukov@gmail.com
