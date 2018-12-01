# Ansible role docker

This is an ansible role to install docker.

## Installation

```
$ ansible-galaxy install tottoto.docker
```

## Example

```yaml
- name: Example playbook to use tottoto.docker
  hosts: all
  become: yes
  roles:
    - tottoto.docker
```
