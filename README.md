andrewrothstein.kubic
=========
![Build Status](https://github.com/andrewrothstein/ansible-kubic/actions/workflows/build.yml/badge.svg)

Installs the Kubic package repo into apt.

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
    - andrewrothstein.kubic
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
