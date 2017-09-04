postgresql
==========

Deploy a Postgres RDBMS for development purpose.  

Requirements
------------

Ansible and an internet connection


Role Variables
--------------

* `postgresql_user` is the linux user PostgreSQL runs under
* `postgresql_data_dir` is the location on disk data files are stored
* `postgresql_max_connections` is the maximum number of connection allowed
* `postgresql_allow_remote_connections` indicates whether or not to allow connections from other computers

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: servers
  roles:
     - { role: quocvu.postgresql, postgresql_max_connections: 10 }
```

License
-------

MIT

Author Information
------------------

Quoc Vu  
https://linkedin.com/in/quocvu  
