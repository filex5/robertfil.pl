Role Name
=========

donfilemon.grafana

Requirements
------------

Ubuntu with Systemd and ansible > 2.4 

Role Variables
--------------

graphana_version: 



Dependencies
------------

none 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

   - hosts: monitoring-server
  become: true
  roles:
    - donfilemon.grafana
  vars:
    graphana_version: 5.2.1

License
-------

MIT

Author Information
------------------

Robert Fil Don Filemon ( filex5 )
