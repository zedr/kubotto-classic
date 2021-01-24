# k8s from scratch
Ansible Playbooks to install a custom, single-node Kubernetes cluster,
from scratch.

Based on [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)

Updated to Kubernetes 1.20.0.

## Supported architectures

 - amd64
 - arm

Set using extra var `arch`, e.g. `-e arch=arm64`.

## Caveats

 - SELinux is disabled, for now.

## Dependencies

 - Vagrant
 - libvirtd
 - libvirtd-vagrant
