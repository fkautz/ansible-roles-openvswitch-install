OpenVSwitch
=========

Installs OpenVSwitch.

Based on ODL releng/build example, adapted as a role and adds RHEL support.

Requirements
------------

RHEL or Ubuntu

Role Variables
--------------

openvswitch_version
openvswitch_checksum

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: fkautz.openvswitch-install }

License
-------

Apache License V2

Author Information
------------------

Frederick F. Kautz IV - Red Hat
