mysql
=========

Ansible role for mysql (Ubuntu server).

Role Variables
--------------

    mysql_users: [{name: 'user', password: 'password', db: 'mydb'}]

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: webbylab.mysql
           mysql_users: [{name: 'user', password: 'password', db: 'mydb'}]

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)
