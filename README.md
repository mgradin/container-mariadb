Role Name
=========

Deploy official mariadb container.

Requirements
------------

None

Role Variables
--------------

defaults:
VAR_MARIADB_DIR: /opt/mariadb
VAR_MARIADB_PASSWORD: mariadbpasswd

Dependencies
------------

None

Example Playbook
----------------

- hosts: server
  roles:
    - role: container-mariadb
      tags: [ mariadb ]

License
-------

BSD

Author Information
------------------

Mathias Gradin
