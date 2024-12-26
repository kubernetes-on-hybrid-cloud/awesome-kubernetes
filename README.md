# Awesome Kubernetes resources for hybrid environment installation

Contributions welcome!

### Template

* **[Project/User name](Project/Repository URL)** - Description & Use cases

## Kubernetes distributions

* **[Rancher](https://rancher.com/)** - Kubernetes management platform.
* **[Talos](https://talos.dev/)** - Immutable and minimal Kubernetes distribution.

## Base components

The projects below are the base components that are used to integrate Kubernetes with the cloud providers.

### Cloud Controller Manager

The list of CCMs that are hybrid cloud ready

* **[Talos CCM](https://github.com/siderolabs/talos-cloud-controller-manager)** - CCM for Talos
* **[Proxmox CCM](https://github.com/sergelogvinov/proxmox-cloud-controller-manager)** - CCM for Proxmox VE

### Container Storage Interface

* **[Proxmox CSI](https://github.com/sergelogvinov/proxmox-csi-plugin)** - CSI driver for Proxmox VE
* **[OpenStack Cinder CSI](https://github.com/kubernetes/cloud-provider-openstack)** - CSI driver for OpenStack Cinder

### Node Autoscaler

* **[Kubernetes Node Autoscaler](https://github.com/kubernetes/autoscaler)** - Autoscaler for Kubernetes

## Tools

Tools and utilities that are used to manage cluster or workloads in hybrid environments.

## Examples and tutorials

Please add examples and tutorials that are related to hybrid cloud installations here.

* **[Talos on hybrid environment](https://github.com/sergelogvinov/terraform-talos)** - Terraform examples for Azure, GCP, Hetzner, OVH, Oracle, Proxmox, Scaleway cloud providers.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0)
