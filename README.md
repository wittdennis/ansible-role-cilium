Role Name
=========

Role to manage cilium installation


Role Variables
--------------

```
cilium_version: "1.15.1" # Version of cilium to use
cilium_cli_version: "v0.15.23" # Version of cilium cli to use
cilium_enable_hubble: false # Flag to control if hubble should be enabled
```

Example Playbook
----------------

    - hosts: control_plane
      roles:
          - { role: wittdennis.cilium }

License
-------

MIT
