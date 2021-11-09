Logindefs Role
=========

This role will configure the `/etc/login.defs` file based on a template and variables.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.logindefs-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-logindefs/)


Requirements
------------

All requirements met by default ansible tooling.

Role Variables
--------------

An example list of all variables for this role should go here, including any variables that are in defaults/main.yml and vars/main.yml. Any variables that are read from other roles and/or the global scope (e.g. hostvars, groupvars, etc) should be shown here also.


```yaml
logindefs_configure: True
logindefs_pass_max_days: 180
logindefs_pass_min_days: 1
logindefs_pass_warn_age: 14
logindefs_env_supath: "PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin"
logindefs_env_path: "PATH=/usr/local/bin:/usr/bin:/bin:/usr/local/games:/usr/games"
```

Refer to the `defaults/main.yml` file for full details.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - neoloc.logindefs

License
-------

See license.md

Author Information
------------------

[![Github](https://img.shields.io/badge/Github-neoloc-blue.svg)](https://github.com/neoloc)
