ansible-kibana role
===================

This role installs kibana.

Variables
----------

- `kibana_plugins`: plugin list to install (default: [])

Tests
-----

Test can then be run using vagrant:

```
vagrant up
vagrant ssh -c specs
```

Licence
-------

MIT

Authors
-------
@leucos - Michel Blanc
