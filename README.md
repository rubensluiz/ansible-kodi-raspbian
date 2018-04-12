kodi-raspbian
=========

Ansible role for Kodi.tv. Currently this works on Raspbian. Tested platforms are:
* Raspbian GNU/Linux 9

Example Playbook
----------------

memory_split var is mandatory

    - hosts: servers
      roles:
         - { role: rubensluiz.kodi-raspbian, memory_split: 256 }

License
-------

BSD
