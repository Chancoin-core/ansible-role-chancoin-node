Chancoin-node
=========



Requirements
------------

None - yet.

Role Variables
--------------

None yet

Dependencies
------------
* gantsign.golang

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: chancoin.chancoin_node }

License
-------

BSD

Author Information
------------------

Maintained by Chancoin-core team


TODO
* Test this guy in docker
* Copy over address if present
* Parameterize bootnodes as var in toml file
* Add enable_service var with default of true

DONE
* Add install path var with default of /opt/chancoin
* Add enable_service var with default of true
* Copy over address if present
* Add install path var with default of /opt/chancoin
* Are we running with the toml file as config?
