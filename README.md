# Ansible Role: motd


## Role Variables


| Name           | Default  | Type    | 
| -------------- | -------- | ------- |
| `logotext`     | Server   | String  |
| `environement` | default  | String  |

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - role: norskel.motd
          vars:
              logotext: Norskel
              environement: default

## Example MOTD
        _   __                __        __
       / | / /___  __________/ /_____  / /
      /  |/ / __ \/ ___/ ___/ //_/ _ \/ /
     / /|  / /_/ / /  (__  ) ,< /  __/ /
    /_/ |_/\____/_/  /____/_/|_|\___/_/

    -----------------------------------------------------------------------------
            Environement  : default
            Hostname      : test.norskel.test
            IP            : 192.168.0.1
            OS            : CentOS 8.3
    -----------------------------------------------------------------------------
