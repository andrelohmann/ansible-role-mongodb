mongodb
=======

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-mongodb.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-mongodb)

Deploy mongodb to your machine

Role Variables
--------------

Set the MongoDB Version, that you like to get installed.

    mongodb_version: "4.0"

Example Playbook
----------------

    - hosts: mongodb
      roles:
         - andrelohmann.mongodb

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
