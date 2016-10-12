## ansible-perl - [![Build Status](https://travis-ci.org/grimmjow8/ansible-perl.png)](https://travis-ci.org/grimmjow8/ansible-perl)

Ansible role installs cpanm and generally useful perl modules from CPAN.

Requirements
------------

- Tested on ansible 2.1.2.0

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: grimmjow8.ansible-perl }


Testing
-------
\<path\>/ansible-perl $ ansible-playbook test.yml 


License
-------

Licensed under the MIT License. See the LICENSE file for details.

Author Information
------------------

TBD
