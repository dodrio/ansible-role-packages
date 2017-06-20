# packages

[![Build Status](https://travis-ci.org/m31271n/ansible-role-packages.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-packages)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.packages-blue.svg)](https://galaxy.ansible.com/m31271n/packages)

Ansible role that installs packages.

## Requirements

None.

## Role Variables

+ `packages`: default `[]`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.packages
      packages:
        - epel-release
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
