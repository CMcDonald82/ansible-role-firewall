# ansible-role-firewall

[![Build Status](https://travis-ci.org/CMcDonald82/ansible-role-firewall.svg?branch=master)](https://travis-ci.org/CMcDonald82/ansible-role-firewall)

Ansible role for installing and configuring a firewall using UFW on an Ubuntu server


## Requirements

None

## Role Variables

None

## Example Playbook

```
- name: Install and configure UFW firewall on Ubuntu server
  hosts: all
  remote_user: "{{ remote_username }}"
  become: yes

  roles:
    - role: firewall_role
```

## Dependencies

None