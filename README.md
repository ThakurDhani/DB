# ScyllaDB Role

## Description
Installs and configures ScyllaDB on Ubuntu.

## Requirements
- Ubuntu
- Ansible 2.9+

## Example Playbook
```yaml
- hosts: scylla
  roles:
    - scylladb
