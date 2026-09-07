# armpve9docker
armpve9docker base from detain 13 trixie

在debain13 arm64 docker基础上安装pve9的源，用于编译pve9上的各种软件使用，比如项目https://github.com/AICodo/pve-emu-realpc 就在使用这个docker进行编译pve-qemu deb

This Docker image is based on Debian 13 arm64 with Proxmox VE 9 repositories configured, designed for compiling various software packages on Proxmox VE 9. For instance, the project https://github.com/AICodo/pve-emu-realpc uses this Docker environment to compile PVE-QEMU Debian packages.


如何使用：

Usage:

docker pull ghcr.io/AICodo/armpve9docker:main
