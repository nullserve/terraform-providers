# terraform-providers

This repository is used for storing [third-party plugin terraform providers](https://www.terraform.io/docs/configuration/providers.html#third-party-plugins).
Terraform requires that these plugins be pre-built for execution, so this repository will only store binaries.
The layout of this repository is designed to fit with [Terraform Cloud's reccomended install process for third-party plugins](https://www.terraform.io/docs/cloud/run/install-software.html).
This repository is used primarily as a submodule to the [infrastructure repository](https://github.com/nullserve/infrastructure)
All modules are added to master.
It is recommended that any issues with third-party providers be fixed-forward and that we do not maintain multiple versions of a third-party plugin.
