terraform
=================

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-terraform.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-terraform)

Use this role to install terraform.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    terraform_version: 0.11.14

Example Playbook
----------------

    - hosts: terraform
      roles:
         - { role: andrelohmann.terraform }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
