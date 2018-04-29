ansible-ntp
=========
[![Build Status](https://travis-ci.org/boxrick/ansible-ntp.svg?branch=master)](https://travis-ci.org/boxrick/ansible-ntp)

This role installs and configures ntp with some simple defaults.

Requirements
------------

This module requires Ansible 2.4

Role Variables
--------------

See defaults for variables and descriptions

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: ansible-ntp }
