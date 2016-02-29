ansible-role-dnsclient
=========

[![Build Status](https://travis-ci.org/ofsole/ansible-role-dnsclient.png?branch=master)](https://travis-ci.org/ofsole/ansible-role-dnsclient)

This module manages /etc/resolv.conf file and its various options

Requirements
------------

none.

Role Variables
--------------

nameservers, options, search, domain, sortlist, resolver_config_file, resolver_config_file_owner, resolver_config_file_group, resolver_config_file_group could be customized in dnsclient role

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: dnsclient
           nameservers:
             - 147.128.74.79
             - 147.128.68.204
             - 8.8.8.8
           search:
             - google.cn
             - google.com

License
-------

BSD

Author Information
------------------

Elvis Cai
