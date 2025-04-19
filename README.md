Role Name
=========

This role applies journald storage limits.

Requirements
------------

None.

Role Variables
--------------

Set the variable `journald_limits` to override the default of 500 Megabytes.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - sachapan.journald

License
-------

GPL 3.0

Author Information
------------------

https://github.com/sachapan