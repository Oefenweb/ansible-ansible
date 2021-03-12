## ansible

[![CI](https://github.com/Oefenweb/ansible-ansible/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-ansible/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-ansible-blue.svg)](https://galaxy.ansible.com/Oefenweb/ansible)

Set up (the latest version of) Ansible in Debian-like systems.

#### Requirements

* `pip` (will not installed)
* `python(2|3)` (will be installed)
* `python-dev(2|3)` (will be installed)
* `build-essential` (will be installed)
* `libffi-dev` (will be installed)
* `libssl-dev` (will be installed)

#### Variables

* `ansible_python_version_major` [default: `2`]: Python version to install `ansible` for.
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
