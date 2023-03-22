# Ansible role: Burp Suite Enterprise

Ansible role to install Burp Suite Enterprise Agent for Linux.
base from iesplin.burp_suite https://github.com/iesplin/ansible-role-burpsuite

## Requirements

This role requires the `jmespath` Python library to be present on the host running the playbook for `json_query` filters.

## Example playbooks

```yaml
- hosts: localhost
  become: true
  roles:
    - roles/burpsuite
```

## License

MIT
