Repo\_ppa
=========

Role install passenger repo from https://oss-binaries.phusionpassenger.com/apt/passenger.

Requirements
------------

Works only on Debian like systems.

Role Variables
--------------

state: 
  - present: Ensure repository is available (default)
  - absent: Ensure repository is not available.

Example Playbook
----------------

    - hosts: passenger_servers
      roles:
         - { role: davidkarban.repo_passenger }

License
-------

GPLv3

Author Information
------------------

email: david@karban.eu

github: davidkarban

web: www.karban.eu

