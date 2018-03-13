# Ansible Role: motd

[![Build Status](https://travis-ci.org/arillso/ansible.motd.svg?branch=master)](https://travis-ci.org/arillso/ansible.motd) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/er/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-motd-blue.svg)](https://galaxy.ansible.com/arillso/motd)

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

## Changelog

### 1.2

* add debian Support

### 1.1

* add support for dynamic motd

### 1.0

* inital role

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher