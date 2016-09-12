andrewrothstein.elasticsearch-cluster
=====================================

A role to configure an elasticsearch cluster member. We assume that there's one Ansible host group
that contains all of the hosts to include in the cluster. That group defaults to 'elasticsearch' but
is configurable with the 'elasticsearch_group_name' var.

Requirements
------------

See [meta/main.yml]

Role Variables
--------------

See [defaults/main.yml]

Dependencies
------------

See [meta/main.yml]

Example Playbook
----------------

    - hosts: elasticsearch-cluster-group
      roles:
         - role: elasticsearch-cluster
	   elasticsearch_group_name: elasticsearch-cluster-group

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
