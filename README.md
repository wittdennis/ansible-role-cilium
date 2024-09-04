# cilium

Role to manage cilium installation

## Role Variables

```
cilium_version: "1.15.1" # Version of cilium to use
cilium_cli_version: "v0.15.23" # Version of cilium cli to use
cilium_enable_hubble: false # Flag to control if hubble should be enabled
cilium_helm_values: {} # Additional helm values to use for install and upgrade
cilium_upgrade_always: false # Flag to always run upgrade. Useful when adjusting helm values.
```

## Example Playbook

    - hosts: control_plane
      roles:
          - { role: wittdennis.cilium }

## License

MIT
