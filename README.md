# Ansible role - libvirt

## Description
Ansible role `libvirt`


## Requirements
- Ansible 2.7
- OS Platforms:
  - Ubuntu 18.04 bionic


## Dependencies
None


## Variables
Variables are prefixed by `libvirt__`

| Variable       | Choices | Default                              | Description             |
| -------------- | ------- | ------------------------------------ | ----------------------- |
| `packages`     |         | `["libvirt-bin","qemu"]`             | Packages to install     |
| `dependencies` |         | `["python3-libvirt","python3-lxml"]` | Packages need for role  |
|                |         |                                      |                         |
| `pools`        | See [defaults](defaults/main.yml)  | `[]`      | Pools to be managed     |
| `volumes`      | See [defaults](defaults/main.yml)  | `[]`      | Volumes to be managed   |
| `metadatas`    | See [defaults](defaults/main.yml)  | `[]`      | Metadatas to be managed |
| `networks`     | See [defaults](defaults/main.yml)  | `[]`      | Networks to be managed  |
| `domains`      | See [defaults](defaults/main.yml)  | `[]`      | Domains to be managed   |


## License
[MIT](https://opensource.org/licenses/MIT)


## Authors
Jose Castro \<jfcastroluis@gmail.com\>
