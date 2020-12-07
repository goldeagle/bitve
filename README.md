# BITVE
A BITseed Virtual Enviroment linux distribution, based on debian &amp; kubernetes &amp; CNCF components, with build-in compile toolchain.

This is an *experimental* project currently, do NOT use it in your production enviroment.

# Architecture
- Based on Debian sid branch
- Support x86_64 and Aarch64 CPUs
- Kubernetes
- CNCF components
- Dual Shim runtime
- Hot-swap system rootfs for online upgrade

# Technical Stack (2020-12-07)

## Operating System
- based on Debian sid
- x86_64 (AMD64) supported
- Arrch (ARMv8) supported

## Virtual Enviroment
- Kubernetes 1.20.0-rc0
- CRI-O 1.9.9
- containerd 1.4.1
- RunC 1.0.0-rc92
- Kata Containers 2.0.0-rc1
- Helm 3.4.1

## Componets
- CoreDNS 1.8.0
- Etcd 3.4.9
- Traefik 2.3.2
- Traefik Mesh 1.4.1
- Grafana 7.3.4
- TDengine 2.0.8.0
- Gitea 1.13.0

## Build-in Toolchain
- gcc 10.2.0-23
- rust 1.48.0
- go 1.15.5

## Toolits
* htop 3.0.2-1
* iotop 1.15-1
* iftop 1.0~pre4-7
* bwm-ng 0.6.2-1
* unzip 6.0-25
* curl 7.72.0-1
* vim 8.2.1913-1
* nmap 7.91-1
* dstat 0.7.4-6
* byobu 5.133-1
* tmux 3.1c-1
* multitail 6.5.0-2
* mtr 0.94-1
* netcat 1.10-46
* socat 1.7.3.4-1
* ranger 1.9.3-2
* net-tools 1.6.0
