# nginx_role

This Ansible role installs and configures Nginx on Debian/Ubuntu systems.

## Features

- Installs Nginx
- Starts and enables the Nginx service
- Creates a custom index.html file

## Requirements

- Ansible
- Debian/Ubuntu target system

## Role Variables

No required variables.

## Example Playbook

```yaml
- hosts: localhost
  connection: local
  become: yes

  roles:
    - nginx_role
