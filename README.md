
# Coriolis ansible install script

This ansible script installs coriolis with all dependencies on Ubuntu 14.04.5 LTS. An Vagrantfile is provided to setup everything in a vm.

## Install

For initial setup run:

```
~/ansible-coriolis: vagrant up
```

This installs the vm and does ansible provisioning.

To apply changes in Vagrantfile, like other OS version, please run:

```
~/ansible-coriolis: vagrant provision
```

## Author

Stefan Helmert


