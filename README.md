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

To disable and only install bdii set variables like so:

<pre>
umd_repo_file: False
umd_repo_rpm: False
site_bdii_enabled: True
site_bdii_packages:
 - bdii

site_bdii_files: []
site_bdii_site_urls: []
site_bdii_glite_info_site_defaults: []

# set site_bdii_conf_enabled to True to add more config lines to bdii.conf
site_bdii_conf_enabled: True
</pre>




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
