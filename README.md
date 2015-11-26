## ansible

[![Build Status](https://travis-ci.org/Oefenweb/ansible-ansible.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-ansible) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-ansible-blue.svg)](https://galaxy.ansible.com/list#/roles/5782)

Set up (the latest version of) Ansible in Debian-like systems.

#### Requirements

* `pip` (will not installed)

* `python` (will be installed)
* `python-dev` (will be installed)
* `build-essential` (will be installed)

#### Variables

* `ansible_ansible_version`: [default: `latest`]: Ansible version to install (e.g. `latest`, `1.9.2`)

## Dependencies

None

## Recommended

* `ansible-pip` ([see](https://github.com/Oefenweb/ansible-pip))
* `ansible-virtualenv` ([see](https://github.com/Oefenweb/ansible-virtualenv))

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
