Role Name
=========


Requirements
------------



Role Variables
--------------

satellite_default_location
satellite_default_organization
satellite_enable_discovery
satellite_enable_tftp
hostname
satellite_user
satellite_pass
satellite_packages
rhsm_repos
satellite_default_location
satellite_default_organization
satellite_enable_tftp
satellite_enable_discovery

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
