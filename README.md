Role Name
=========

Install php

Requirements
------------

None

Role Variables
--------------

- php_remi_version: php version from remi repo (es:"remi-php56")

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      vars:
        php_remi_version: "remi-php56"
      roles:
         - php

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
