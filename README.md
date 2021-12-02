Ansible Role: Win-Aksiok
=========

Эта роль установит ППО «АКСИОК» релиз aksios20.06.28 на ОС Windows.
Версия для СУБД MS SQL Server

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены вместе со значениями по умолчанию (см. `defaults/main.yml`).
Роль установит клиентскую часть и сервисный модуль на рабочую станцию, для подключения к серверу с базой данных используйте свой файл connect.cfg!

Dependencies
------------

Внимание для корректной выгрузки файлов из ППО «АКСИОК» необходим пакет Microsoft Excel 32bit.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - win_aksiok

License
-------

BSD

Author Information
------------------

Chubik Sergey, sergey.chubik@mail.ru.
Chubik Sergey, chubik@ekaterinburg.fsin.uis.
