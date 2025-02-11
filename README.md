Elasticsearch
=========

Deploy the ES service running under the container via ansible.

Installation
------------

`ansible-galaxy install gengxiankun.mysql`

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - gengxiankun.elasticsearch
      vars:
        OPT_PATH: /opt
        ELASTIC_PASSWORD: 123456
        ELASTIC_VERSION: 8.15.3
        ES_PORT: 9200
        KIBANA_PASSWORD: 123456
        KIBANA_PORT: 5601

License
-------

BSD

Author Information
------------------

This role was created in 2025 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
