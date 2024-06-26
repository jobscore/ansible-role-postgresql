PostgreSQL
=========
[![CI](https://github.com/jobscore/ansible-role-postgresql/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/jobscore/ansible-role-postgresql/actions/workflows/ci.yml)

An Ansible role for installing PostgreSQL from source on an Ubuntu box.

Requirements
------------

None

Role Variables
--------------

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
       postgresql_version: 15.4
```
License
-------

[GPLv3](/LICENSE)

Author Information
------------------

This role was created by [Eric Magalhães](https://emagalha.es) and [Glauber Batista](https://glauberrbatista.dev) while working for [JobScore Inc](https://jobscore.com).
