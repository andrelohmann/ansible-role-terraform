terraform
=========

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-terraform.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-terraform)

Use this role to install terraform.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    terraform_version: 0.14.7 #defaults to 'latest'

Example Playbook
----------------

    - hosts: terraform
      roles:
         - andrelohmann.terraform

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
