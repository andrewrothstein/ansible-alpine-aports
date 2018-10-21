andrewrothstein.alpine-aports
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-alpine-aports.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-alpine-aports)

Stuff for building Alpine Linux packages and ISOs

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.alpine-aports
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
