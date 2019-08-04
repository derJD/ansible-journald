journald
========

Managing content of [journald.conf](https://www.freedesktop.org/software/systemd/man/journald.conf.html) and reload journald on change.

Requirements
------------

All you need is a system with systemd.

Role Variables
--------------

| Variable | Type | Default | Description |
| -------- | ---- | ------- | ----------- |
| `journald_options` | dict | `{Storage: persistent, SystemMaxUse: 4G}` | Dict accepting all values described in [journald.conf](https://www.freedesktop.org/software/systemd/man/journald.conf.html) |

Dependencies
------------

No dependencies so far.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - derJD.journald

License
-------

BSD

Author Information
------------------

[derJD](https://github.com/derJD)
