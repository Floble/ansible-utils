Chrony
=========

Ansible role for installing and configuring Chrony.

Requirements
------------

None.

Role Variables
--------------

| Variable  | Description |
| ------------- | ------------- |
| time_server  | NTP server to sync with  |

Dependencies
------------

None.

Example Playbook
----------------
    - hosts: all
      vars:
        time_server: time.google.com
      roles:
        - role: chrony

License
-------

MIT

Author Information
------------------

Floble