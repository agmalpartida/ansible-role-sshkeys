# Ansible Role: ssh-keys-add

[![Build Status](https://api.travis-ci.com/agmalpartida/ssh-keys-add.svg?branch=master)](https://travis-ci.com/github/agmalpartida/ssh-keys-add)

Given a list of usernames, this Ansible role upload their SSH public keys and adds them to ~/.ssh/authorized_keys

Requirements
------------

* `httplib2` - installed automatically via PIP

Role Variables
--------------

```
ssh_keys_local_path: "ssh-keys"  # relative to ./files

ssh_keys_usernames_add:
  - example
```


License
-------

BSD

Author Information
------------------

agmalpartida
