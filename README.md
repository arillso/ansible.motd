# Ansible Role: motd

## Description

Creates the motd file.

## Installation

```
$ ansible-galaxy install arillso.motd
```

## Requirements

None 

## Example Motd

'''
     _              _ _     _
    / \   _ __  ___(_) |__ | | ___
   / _ \ | '_ \/ __| | '_ \| |/ _ \
  / ___ \| | | \__ \ | |_) | |  __/
 /_/   \_\_| |_|___/_|_.__/|_|\___|

--------------------------------------------------------------------------
                    This system is managed by Ansible
--------------------------------------------------------------------------

 FQDN:                ansible.example.ch
 Distro:              CentOS 7.3.1611 Core
 Virtual:             YES
 Virtualization Type: kvm

 CPUs:                1
 RAM:                 1.0GB
 Swap:                2.0GB
 Timezone:            CET(+0100)


 Mount: /dev/mapper/centos_ansible-root(/)(17.5GB)
 Mount: /dev/vda1(/boot)(0.5GB)

 Interfaces:
  Interface: lo
   ip: 127.0.0.1
  Interface: eth0
   ip: 192.168.0.0
   mac: 00:1a:67:16:11:52

'''

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - arillso.motd
```

## Changelog

### 1.0

* inital role

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher