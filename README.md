# [snmpd](#snmpd)

Install and configure SNMP on Linux and Windows.

Inspired by:
  * https://github.com/sbaerlocher 
  * https://github.com/robertdebock

## [Example Playbook](#example-playbook)

```yaml
---
- name: converge
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: ansible-role-snmp
```

## [Role Variables](#role-variables)

The default values for the variables are set in `defaults/main.yml`:
## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/kbcz1989/ansible-role-snmp/blob/master/requirements.txt).

