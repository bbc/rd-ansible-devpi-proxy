rd-ansible-devpi-proxy [![Build Status](https://travis-ci.org/bbc/rd-ansible-devpi-proxy.svg?branch=master)](https://travis-ci.org/bbc/rd-ansible-devpi-proxy)
=========

This module installs devpi which then acts as a caching pypi proxy server

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
         - { role: rd-ansible-devpi-proxy }
