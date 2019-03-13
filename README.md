TEACUP node
=========

A role for configuring TEACUP experiment running nodes.

Requirements
------------

None besides working SSH access and a way to raise privileges.

Role Variables
--------------

Check vars/main.yml for download URLs for some modified tools that TEACUP expects to find.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: testnodes
      roles:
         - teacup_node

License
-------

BSD

Author Information
------------------

Kristian A. Hiorth <kristahi@ifi.uio.no>
University of Oslo
