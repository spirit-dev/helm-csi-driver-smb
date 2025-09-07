# CHANGEME

[![GitLab Sync](https://img.shields.io/badge/gitlab_sync-csi_driver_smb-blue?style=for-the-badge&logo=gitlab)](https://gitlab-internal.spirit-dev.net/github-mirror/helm-csi-driver-smb) <!-- markdownlint-disable MD041 -->
[![GitHub Mirror](https://img.shields.io/badge/github_mirror-csi_driver_smb-blue?style=for-the-badge&logo=github)](https://github.com/spirit-dev/helm-csi-driver-smb)
[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=csi-driver-smb-turingpi&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/csi-driver-smb-turingpi)

<!--TOC-->

- [Docker images](#docker-images)
- [Installation process](#installation-process)
- [Examples](#examples)
- [Resources](#resources)

<!--TOC-->

## Docker images

We can scroll through the `registry.k8s.io` using the following website: <https://explore.ggcr.dev/?repo=registry.k8s.io%2Fsig-storage%2Fsmbplugin>

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
