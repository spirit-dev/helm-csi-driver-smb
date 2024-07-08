# Welcome to csi-driver-smb

## Table of content

- [Welcome to csi-driver-smb](#welcome-to-csi-driver-smb)
  - [Table of content](#table-of-content)
  - [Installation process](#installation-process)
  - [Examples](#examples)
  - [Resources](#resources)

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
