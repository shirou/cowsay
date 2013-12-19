cowsay
===============

This role will install Ansible-most-important-prerequirement software.


Requirements
---------------------

Needs sudo.

Role Varibles
-----------------

Nothing yet.

Example
---------------

    - hosts: localhost
      connection: local
      sudo: yes
      roles:
          - {role: r_rudi.cowsay}

Dependencies
-----------------

None

License
-------

2-clause BSD

Author Information
------------------

WAKAYAMA Shirou


Notice
------

If you want to disable cowsay, set environment variable ANSIBLE_NOCOWS=1  or nocows=1 at ansible.cfg.

