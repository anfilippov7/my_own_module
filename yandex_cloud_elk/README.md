# Ansible Collection - my_own_namespace.yandex_cloud_elk

Коллеция для записи текствого файла на хост
 - содержит плейбук (site.yml) который использует роль (file-role) 
 - роль использует модуль (my_own_module.py) для создания текстового файла на удалённом хосте по заданному пути.

Role Variables
path - задает путь и имя файла который будет создан.
content - задается строка которая будет добавлена в файл

Example Playbook
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- name: My own module
  hosts: localhost
  roles:
    - file-role

```
License
MIT

Author Information
Aleksander Filippov
