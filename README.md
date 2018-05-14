Role Name
=========

A small ansible role to setup my bashrc config for a user.

Requirements
------------

Only core modules for now.

Role Variables
--------------

 * bashrc_username: username
 * bashrc_groupname: primary groupname of the user
 * bashrc_homedir: homedir of the user

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      vars:
        bashrc_username: jvzantvoort
        bashrc_groupname: jvzantvoort
        bashrc_homedir: "/home/{{ bashrc_username }}"

      roles:
        - jvzantvoort.bashrc


License
-------

MIT

Author Information
------------------

John van Zantvoort
