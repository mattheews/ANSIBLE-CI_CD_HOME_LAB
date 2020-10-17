Role Name
=========

TASK [../roles/docker_compose : Download docker-compose from GitHub] ***************************************************************************
An exception occurred during task execution. To see the full traceback, use -vvv. The error was: InvalidURL: URL can't contain control characters. '/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)' (found at least ' ')
fatal: [192.168.2.7]: FAILED! => {"changed": false, "content": "", "elapsed": 0, "msg": "Status code was -1 and not [200]: An unknown error occurred: URL can't contain control characters. '/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)' (found at least ' ')", "path": "/usr/local/bin/docker-compose", "redirected": false, "status": -1, "url": "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)"}

FIX IT!!!

Requirements
------------

TBD

Role Variables
--------------

TBD

Dependencies
------------

TBD

Example Playbook
----------------

TBD

License
-------

BSD

Author Information
------------------

Mateusz Sobociński
mateusz.sobocinski7912@gmail.com