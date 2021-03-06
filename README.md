# Ansible Role for Vagrant

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-vagrant/master)](https://gitlab.com/alvistack/ansible-role-vagrant/-/pipelines)
[![GitHub release](https://img.shields.io/github/release/alvistack/ansible-role-vagrant.svg)](https://github.com/alvistack/ansible-role-vagrant/releases)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-vagrant.svg)](https://github.com/alvistack/ansible-role-vagrant/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.vagrant-blue.svg)](https://galaxy.ansible.com/alvistack/vagrant)

Ansible Role for Vagrant Installation.

## Requirements

This role require Ansible 2.10 or higher.

This role was designed for:

  - Ubuntu 18.04, 20.04, 20.10
  - CentOS 7, 8, 8 Stream
  - openSUSE Leap 15.2, Tumbleweed
  - Debian 10
  - Fedora 33
  - RHEL 7, 8

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

  - Wong Hoi Sing Edison
      - <https://twitter.com/hswong3i>
      - <https://github.com/hswong3i>
