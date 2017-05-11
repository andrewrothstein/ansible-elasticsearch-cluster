andrewrothstein.elasticsearch-cluster
=====================================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-elasticsearch-cluster.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-elasticsearch-cluster)

A role to configure an elasticsearch cluster member.

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
- hosts: elasticsearch
  roles:
    - andrewrothstein.elasticsearch-cluster
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
