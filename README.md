Role Name
=========

Install redis stable version on Linux.

Role Variables
--------------

**redis_download_url**
**redis_port** 
**redis_databases_nums**
**redis_dump_dir**
**redis_maxclient**
**redis_maxmemory**
**redis_password**
**redis_conf_path**

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

---
- hosts: localhost
  remote_user: root
  roles:
    - ansible-role-redis

License
-------

BSD

Author Information
------------------

This role was created by nilnaijgnid.
