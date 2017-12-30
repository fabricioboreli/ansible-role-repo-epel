Repo EPEL
=========
Ansible Role that install EPEL Repo on CentOS.

Requirements
------------
CentOS 7  

Role Variables
--------------
None.

Dependencies
------------

None.

Example Playbook
----------------
```yaml
---
- name: Install EPEL Repo on CentOS 7
  hosts: webserver01
  become: true
  gather_facts: true

  roles:
    - role: ansible-role-repo-epel
```

License
-------
MIT

Author Information
------------------

Fabricio Boreli  
fabricioboreli at openmailbox dot org
