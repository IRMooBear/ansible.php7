[![Build Status](https://travis-ci.org/IRMooBear/ansible.php7.svg?branch=master)](https://travis-ci.org/IRMooBear/ansible.php7)

PHP 7
=========
This Ansible role compile PHP 7 as defined by the variables.

Role Variables
--------------
The two big one, define these and it should compile on AMI and RPI.

    php_version: 7.3.2
    php_checksum: sha256:4597294b00edc1c63a021b6c7838eb43384f62eeb9e392f0b91c38a3c090f499

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename }

License
-------
BSD

Author Information
------------------
An optional section for the role authors to include contact information, or a website (HTML is not allowed).