![Ansible Lint](https://github.com/johanneskastl/ansible-role-update_debian_ubuntu_sources/workflows/Ansible%20Lint/badge.svg)

update_debian_ubuntu_sources
=========

Update the package information on Debian/Ubuntu (i.e. run the equivalent of `apt-get update`).

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.update_debian_ubuntu_sources' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
