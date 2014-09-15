mysql
=========

Ansible role for mysql (Ubuntu server).

Role Variables
--------------

    mysql_users: [{name: 'user', password: 'password', db: 'mydb', host: 'localhost'}]

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: webbylab.mysql
           mysql_users: [{name: 'user', password: 'password', db: 'mydb', host: 'localhost'}]

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)
