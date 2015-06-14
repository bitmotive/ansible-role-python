ansible-role-pythonconf
=========

Python configuration

Requirements
------------

This role has only been tested on EL 6 systems using Ansible 1.9.

Role Variables
--------------

__py_app_source_folder__: Name of the directory that will hold python app files.

__py_app_virtualenv_folder__: Name of the virtualenv folder for the app.

Example Playbook
----------------

```
- hosts: webservers
  roles:
    - { role: bitmotive.ansible-role-pythonconf, tags: "pyapp" }
```

License
-------

MIT
