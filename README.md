Role Name
=========

A small ansible role to setup my bashrc config for a user.

Requirements
------------

Only core modules for now.

Role Variables
--------------

 * ci_username: username
 * ci_groupname: primary groupname of the user
 * ci_homedir: homedir of the user

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      vars:
        ci_username: jvzantvoort
        ci_groupname: jvzantvoort
        ci_homedir: "/home/{{ ci_username }}"

      roles:
        - jvzantvoort.bashrc


License
-------

MIT

Author Information
------------------

John van Zantvoort
