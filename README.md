# Kubotto
Ansible Playbooks to install a custom, single-node Kubernetes cluster,
from scratch.

Based on [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)

- Updated to Kubernetes 1.20.2.
- Uses CRI-O and Podman.
- Runs on CentOS 7.

## Supported architectures

 - amd64
 - arm

Set using extra var `arch`, e.g. `-e arch=arm64`.

## Caveats

 - SELinux is disabled for now.

## Dependencies

 - Vagrant
 - libvirtd
 - libvirtd-vagrant
