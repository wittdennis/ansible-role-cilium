# Changelog
All notable changes to this project will be documented in this file. See [conventional commits](https://www.conventionalcommits.org/) for commit guidelines.

- - -
## [1.3.0](https://github.com/wittdennis/ansible-role-cilium/compare/826c7b6f96d70bbd61eb53740bffd0aabaeee718..1.3.0) - 2024-09-04
#### Features
- implement flag to always execute a cilium upgrade - ([297d3ed](https://github.com/wittdennis/ansible-role-cilium/commit/297d3ed549f8e75db649b9ea7964dee07f82462c)) - Dennis Witt
#### Miscellaneous Chores
- **(deps)** update dependency cilium/cilium-cli to v0.16.16 - ([68c351a](https://github.com/wittdennis/ansible-role-cilium/commit/68c351a55a0f3092a4ba35cc9872e40597527c61)) - wittdennis-renovate[bot]
- **(deps)** update dependency cilium/cilium to v1.16.1 - ([095c7d8](https://github.com/wittdennis/ansible-role-cilium/commit/095c7d8b9c0a8dcc742021a0aba8cc760b7a342e)) - wittdennis-renovate[bot]
- **(deps)** update dependency cilium/cilium-cli to v0.16.15 - ([a15d3d7](https://github.com/wittdennis/ansible-role-cilium/commit/a15d3d707fca57a25d46ffa2235342ab32fd201c)) - wittdennis-renovate[bot]
- **(deps)** update dependency cilium/cilium-cli to v0.16.14 - ([1cbd9cb](https://github.com/wittdennis/ansible-role-cilium/commit/1cbd9cbdf3f79a761edbe96bfc6690781d4bad7d)) - wittdennis-renovate[bot]
- **(deps)** update dependency cilium/cilium to v1.16.0 - ([b853934](https://github.com/wittdennis/ansible-role-cilium/commit/b853934be8e162c3c19cef9e9f79126522c2b8f2)) - wittdennis-renovate[bot]
- **(deps)** update softprops/action-gh-release action to v2.0.8 - ([814c188](https://github.com/wittdennis/ansible-role-cilium/commit/814c1888ac7aa8e61fa4f0ed43aebb659dc64238)) - wittdennis-renovate[bot]
- **(deps)** update softprops/action-gh-release action to v2.0.7 - ([826c7b6](https://github.com/wittdennis/ansible-role-cilium/commit/826c7b6f96d70bbd61eb53740bffd0aabaeee718)) - wittdennis-renovate[bot]

- - -

## [1.2.0](https://github.com/wittdennis/ansible-role-cilium/compare/3274bebab6137028602f5ab969358fec62f46f0a..1.2.0) - 2024-07-18
#### Continuous Integration
- remove unused secrets variable - ([3274beb](https://github.com/wittdennis/ansible-role-cilium/commit/3274bebab6137028602f5ab969358fec62f46f0a)) - Dennis Witt
#### Features
- added ability to specify helm values during install and upgrade - ([df61566](https://github.com/wittdennis/ansible-role-cilium/commit/df61566da92ffb5d22dd049fbe3a9ef3615756e6)) - Dennis Witt
#### Miscellaneous Chores
- **(deps)** update dependency cilium/cilium to v1.15.7 - ([9d907cf](https://github.com/wittdennis/ansible-role-cilium/commit/9d907cfbaa1f8f1598770d1d2e3210a1fe3f32c8)) - wittdennis-renovate[bot]
- **(deps)** update dependency cilium/cilium-cli to v0.16.13 - ([3597aed](https://github.com/wittdennis/ansible-role-cilium/commit/3597aed4142ac8aa912e12bbc2cb53a1e78d6b10)) - wittdennis-renovate[bot]
- **(deps)** update ansible/ansible-lint action to v24.7.0 - ([1751fb9](https://github.com/wittdennis/ansible-role-cilium/commit/1751fb953c939a96aed03b0821e27e5d06ad6e84)) - wittdennis-renovate[bot]
- **(deps)** update dependency cilium/cilium-cli to v0.16.12 - ([3b6c5ae](https://github.com/wittdennis/ansible-role-cilium/commit/3b6c5ae8198fd8bd4be21a05ee56c92b4122f01d)) - wittdennis-renovate[bot]
#### Style
- add pre-commit config - ([6ba21b0](https://github.com/wittdennis/ansible-role-cilium/commit/6ba21b07564c02bfa7c1f15f0e96ceaae4e6e0fe)) - Dennis Witt

- - -

## [1.1.3](https://github.com/wittdennis/ansible-role-cilium/compare/de932cd875eee835a48835af806715826e7d6abb..1.1.3) - 2024-06-29
#### Bug Fixes
- set additional tag for ansible galaxy - ([216f289](https://github.com/wittdennis/ansible-role-cilium/commit/216f28912488a7b22ab3f3ab9a781184a1201c0c)) - Dennis Witt
#### Continuous Integration
- use release token for release workflow - ([de932cd](https://github.com/wittdennis/ansible-role-cilium/commit/de932cd875eee835a48835af806715826e7d6abb)) - Dennis Witt

- - -

## [1.1.2](https://github.com/wittdennis/ansible-role-cilium/compare/4a88fc18dd7a34d705e3f7fd2a7e06a1d2af6074..1.1.2) - 2024-06-29
#### Bug Fixes
- remove sbin symlink for cilium - ([b6ae7f4](https://github.com/wittdennis/ansible-role-cilium/commit/b6ae7f4aef5ea58c485609280e3690e9c71381a3)) - Dennis Witt
#### Miscellaneous Chores
- **(version)** 1.1.1 - ([4a88fc1](https://github.com/wittdennis/ansible-role-cilium/commit/4a88fc18dd7a34d705e3f7fd2a7e06a1d2af6074)) - github-actions

- - -

## [1.1.1](https://github.com/wittdennis/ansible-role-cilium/compare/4a7650c4e7d2469f3587bc4319ecb5bb04f015f9..1.1.1) - 2024-06-29
#### Bug Fixes
- set supported role platforms - ([038bc47](https://github.com/wittdennis/ansible-role-cilium/commit/038bc4720ebf6cd1d3c36ce885b4ba6e52745796)) - Dennis Witt
#### Continuous Integration
- fix release action - ([f9d9f36](https://github.com/wittdennis/ansible-role-cilium/commit/f9d9f36f12d73e7a2cb2e3b4ab5caf455bf684ae)) - Dennis Witt
- setup git config for github-actions - ([0f4af38](https://github.com/wittdennis/ansible-role-cilium/commit/0f4af38169c9539a763167a36f26576356fd9f02)) - Dennis Witt
- fix cog release - ([aaf2a09](https://github.com/wittdennis/ansible-role-cilium/commit/aaf2a09ae2ab8ae98c952c460c25979d4ef1f4ec)) - Dennis Witt
- verify that commits follow conventional commits - ([fe35c80](https://github.com/wittdennis/ansible-role-cilium/commit/fe35c804d669f8c974261e30c4a2c0f9eb4d385b)) - Dennis Witt
#### Documentation
- set role name in README.md - ([bc31f07](https://github.com/wittdennis/ansible-role-cilium/commit/bc31f079038dc3b14e65e1b50176854d0d232a66)) - Dennis Witt
#### Miscellaneous Chores
- implemenent cocogitto - ([4a7650c](https://github.com/wittdennis/ansible-role-cilium/commit/4a7650c4e7d2469f3587bc4319ecb5bb04f015f9)) - Dennis Witt

- - -

Changelog generated by [cocogitto](https://github.com/cocogitto/cocogitto).