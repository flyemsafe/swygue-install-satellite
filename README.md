Role Name
=========


Requirements
------------



Role Variables
--------------

| Variable        | Required | Default  |Description                                                                                                                                                                                                                                     |
| --------------- | -------- | -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|satellite_default_location|:heavy_check_mark: |null| Organization location|
|satellite_default_organization|:heavy_check_mark: |null| Organizaiton organization|
|satellite_enable_discovery|:x:|true||Enabled Discovery Plugin|
|satellite_enable_tftp|:x:|true|Enabled TFTP|
|satellite_domain|:heavy_check_mark: |null|Satellite server domain|
|satellite_hostname|:heavy_check_mark: |null|Satellite server host short name|
|satellite_ip_address|:heavy_check_mark: |null|Satellite server IP addresses|
|satellite_user|:heavy_check_mark: |admin|null|Satellite admin user|
|satellite_pass|:heavy_check_mark: |null|Satellite admin password|
|satellite_firewall_ports|:x:|```defaults/main.yml```|Satellite server required ports|
|satellite_packages|:x:|```defaults/main.yml```|Satellite required pacakges|
|satellite_extra_packages|:x:|```defaults/main.yml```|Useful packages|

Dependencies
------------
- swygue-redhat-subscription

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: swygue-satellite }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
