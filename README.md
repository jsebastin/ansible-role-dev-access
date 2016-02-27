Role Name
=========

modifies /etc/pam.d/common-account
=> adds a linesep argument for use with windows groups with spaces

modifies /etc/security/access.conf
=> adds dev_groups entries

Requirements
------------

None

Role Variables
--------------

dev_groups:
  - Group Name

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-dev-access, dev_groups: ['42'] }

License
-------

BSD

