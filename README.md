Role Name
=========

Install + configure MySQL/MariaDB for: RHEL6, RHEL7, CentOS, Debian, Ubuntu servers.

Requirements
------------

This role requires only root access.

Role Variables
--------------

All default variables that are in defaults/main.yml, vars/main.yml.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:


    - hosts: db-servers
      become: yes
      vars_files:
        - vars/main.yml
      roles:
        - role: ansible-mysql
          become: yes

License
-------

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Author Information
------------------

Maciej Michalski
