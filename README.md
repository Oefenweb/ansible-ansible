## ansible

[![Build Status](https://travis-ci.org/Oefenweb/ansible-ansible.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-ansible) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-ansible-blue.svg)](https://galaxy.ansible.com/list#/roles/4397)

Set up (the latest version of) Ansible in Debian-like systems.

#### Requirements

* `pip` (will not installed)

#### Variables

None

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip)
* `ansible-virtualenv` ([see](https://github.com/Oefenweb/ansible-virtualenv)

#### Example

```yaml
---
- hosts: all
  roles:
    - ansible
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-ansible/issues)!
