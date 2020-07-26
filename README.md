# Vagrant Quickstart

This folder contains Vagrant code to stand up a single Rancher server instance with a node cluster attached to it.
This folder contains Vagrant code to stand up a Rancher RKE cluster.

## Requirements

- [Vagrant](https://www.vagrantup.com)
- [VirtualBox](https://www.virtualbox.org)
- 6GB unused RAM

## Deploy

0. Clone this repository and go into the vagrant subfolder
0. Run `vagrant up`

When provisioning is finished the Rancher UI will become accessible on [](http://172.22.101.101).
The default password is `admin`, but this can be updated in the config.yaml file.

## Remove

To remove the VMs that have been deployed run `vagrant destroy -f`
