# Ansible Role: motd

[![Build Status](https://img.shields.io/travis/arillso/ansible.motd.svg?branch=master&style=popout-square)](https://travis-ci.org/arillso/ansible.motd) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-motd-blue.svg?style=popout-square)](https://galaxy.ansible.com/arillso/motd) [![Ansible Role](https://img.shields.io/ansible/role/d/21815.svg?style=popout-square)](https://galaxy.ansible.com/arillso/motd)

## Description

Configuriet dynamic motd file on Ubuntu and Centos.

## Installation

```bash
 ansible-galaxy install arillso.motd
```

## Requirements

None

## Example Motd

Common

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - arillso.motd
```

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2020, Simon Bärlocher
