# vagrant-dev-box-archlinux
a Vagrant devbox on Archlinux

---
## How to start the Virtual Machine
`vagrant up`
---


## VM configuration
use settings.yml to custom some parameter of the vm

```yaml
vm_name: dev-box-archlinux  # name of the vm
vm_ip: 192.168.50.10        # ip of the vm
vm_mem: 4096                # max ram of the vm
vm_cpus: 4                  # nb cpus of the vm
```
---

## Packages installed

- bash-completion
- firefox
- eclipse-jee
- jre8-openjdk
- maven
- git
- kdiff3m
- meld
- docker
- docker-compose
- xfce4
- xfce4-goodies
- xorg-server
- xorg-server-utils
- xorg-xinit
- lightdm-gtk-greeter
