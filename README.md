# Ansible Role: Discord
[![CI](https://github.com/skaary/ansible-role-discord/actions/workflows/ci.yml/badge.svg?branch=main&event=push)](https://github.com/skaary/ansible-role-discord/actions?query=workflow%3Ci)

An Ansible Role that installs [Discord](https://discord.com/) on Linux.

## Requirements

None

## Dependencies

None

## Installation

Download the role directly from git by typing into your terminal:

```bash
ansible-galaxy install git+https://github.com:skaary/ansible-role-discord.git
```

or

```bash
ansible-galaxy install git+https://github.com:skaary/ansible-role-discord.git,,discord
```

to change the installed role name from _ansible_role_discord_ to just _discord_.

Alternatively, install the role via a _requirements.yml_ file, e.g. when installing multiple roles at once. See [ansible galaxy documentation](https://galaxy.ansible.com/docs/using/installing.html#installing-multiple-roles-from-a-file) for more information.

## Example Playbook

```yaml
- hosts: all
  roles:
    - ansible-role-discord
```

## License

MIT / BSD
