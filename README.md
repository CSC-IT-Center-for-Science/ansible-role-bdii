ansible-role-bdii
=========
[![Build Status](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-bdii.svg?branch=master)](https://travis-ci.org/CSC-IT-Center-for-Science/ansible-role-bdii)

Installs and configures BDII

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

See defaults/main.yml

For the configuration of an site bdii then there are several variables that will probably have to be adjusted.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-bdii }

License
-------

MIT

Author Information
------------------
