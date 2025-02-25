# Welcome to csi-driver-smb

[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=csi-driver-smb-turingpi&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/csi-driver-smb-turingpi)

## Table of content

[[_TOC_]]

## Docker images

We can scroll through the `registry.k8s.io` using the following website: https://explore.ggcr.dev/?repo=registry.k8s.io%2Fsig-storage%2Fsmbplugin

## Installation process

The installation is entirely managed by Argocd.

A `Makefile` is present here to ease the first and one-time deployment or in case of an issue.
The installation should be done in two steps:

```shell
#> make dry-run ENV=<ENV>
#> make install ENV=<ENV>
```

## Examples

- [Examples](examples/Readme.md)

## Resources

- [github](https://github.com/kubernetes-csi/csi-driver-smb)
