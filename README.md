# ansible-system_upgrade

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_upgrade-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_upgrade)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_upgrade.svg)](https://github.com/lotusnoir/ansible-system_upgrade/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_upgrade?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_upgrade)
[![downloads](https://img.shields.io/ansible/role/d/56931)](https://galaxy.ansible.com/lotusnoir/system_upgrade)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56931)](https://galaxy.ansible.com/lotusnoir/system_upgrade)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Upgrade all packages
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

With default variables, this role dont change anything on the system. You need to set the config variables like in the exemple in order to start configuration.

## Examples

        ---
        - hosts: system_upgrade
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_upgrade
          vars:
            upgrade_simulation: false
            upgrade_pkgs_confirmation: false
            upgrade_reboot_confirmation: false
            upgrade_autoreboot: true
            upgrade_clean: true
            upgrade_hold_pkg:
              - grub-pc
              - grub2-common
              - grub-common
              - grub-pc-bin



## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
