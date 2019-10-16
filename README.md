extendi.nvm
=========

Install nvm on Ubuntu

Requirements
------------

None

Role Variables
--------------

    extendi_nvm_version: 6.11.4

node version to install

    extendi_nvm_user: root

install nvm for this user

    extendi_nvm_packages: []

nvm packages to install.
It supports colon syntax to select version to install (e.g. `pm2:2.10.0`)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: nvm-servers
      roles:
         - extendi.nmv

Author Information
------------------

This role was created in 2019 by [Domenico Commisso](mailto:commisso@extendi.it)
