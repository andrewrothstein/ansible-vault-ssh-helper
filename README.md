andrewrothstein.vault-ssh-helper
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-vault-ssh-helper.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-vault-ssh-helper)

Installs Hashicorp's [vault-ssh-helper](https://github.com/hashicorp/vault-ssh-helper)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.vault-ssh-helper
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
