# Ansible Role : manage_selinux

This role reboots a server and waits for the reboot to complete.

## Requirements

None.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.reboot_server

## License

MIT

## Author Information

This role was created in 2021 by Graham Lillico.
