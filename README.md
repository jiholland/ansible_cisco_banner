🪧 banner
==========

Ensure banner for Cisco network-devices.

Requirements
------------

💿 [Cisco IOS Collection](https://galaxy.ansible.com/cisco/ios)<br>
💿 [Cisco NXOS Collection](https://galaxy.ansible.com/cisco/nxos)

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - name: Ensure banner.
      hosts: "{{ target }}"
      gather_facts: false

      roles:
        - role: banner
          tags: banner

License
-------

BSD

Author Information
------------------

Jørn Ivar Holland
