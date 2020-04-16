docker-service
==============

Some services for CHI-in-a-Box are not provided by Kolla-Ansible. This role
provides support for provisioning those services via systemd and Docker.

Requirements
------------

The target host must already have Docker installed. Currently systemd is the only init system supported.

Role Variables
--------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: chameleon.docker-service
           service_name: foo

License
-------

MIT
