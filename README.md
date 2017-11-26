Ansible Role: Tick Stack
=========

Setup TICK Stack (Telegraf, InfluxDB, Chronograf, Kapacitor)

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

* [mlabouardy.docker](https://github.com/mlabouardy/ansible-docker)

Example Playbook
----------------

    - hosts: servers
      remote_user: root
      roles:
         - mlabouardy.tick

License
-------

MIT

Author Information
------------------

Mohamed Labouardy [@mlabouardy](https://twitter.com/mlabouardy)
