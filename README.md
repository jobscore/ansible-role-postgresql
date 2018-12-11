[![Build Status](https://travis-ci.org/jobscore/ansible-role-postgresql.svg?branch=master)](https://travis-ci.org/jobscore/ansible-role-postgresql)

PostgreSQL
=========

An Ansible role for installing PostgreSQL from source on an Ubuntu box.

Requirements
------------

None

Role Variables
--------------

TBD

Check `defaults/main.yml` for more info


Dependencies
------------

None

Example Playbook
----------------

``` yaml
- hosts: servers
  become: true
  roles:
     - role: jobscore.postgresql
       postgresql_version: 9.6.9
```
License
-------

[GPLv3](/LICENSE)

Author Information
------------------

This role was created by [Eric Magalhães](https://emagalha.es) while working for [JobScore Inc](https://jobscore.com).
