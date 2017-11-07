Ansible Role: RPi HWRNG
=========

This role enables Raspberry Pi’s hardware random number generator.

Requirements
------------

Recent Raspbian release - currently Raspbian 9 (Stretch).


Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: pi
      roles:
         - role: mtju.rpi-hwrng
           become: yes

License
-------

The Unlicense

Author Information
------------------

- [Motiejus Ėringis](https://github.com/mtju)
