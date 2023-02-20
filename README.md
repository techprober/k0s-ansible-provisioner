<h1 align="center">K0S Ansible Provisioner</h1>
<p align="center">
    <em>Bootstrap Kubernetes Cluster in Minutes</em>
</p>

<p align="center">
    <img src="https://img.shields.io/github/license/TechProber/k0s-ansible-provisioner?color=critical" alt="License"/>
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FTechProber%2Fk0s-ansible-provisioner&count_bg=%237F3DC8&title_bg=%23555555&icon=kubernetes.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false"/>
    <img src="https://custom-icon-badges.herokuapp.com/badge/kubernetes-v1.23.6+k0s.0-navy.svg?logo=kubernetes&logoColor=white" alt="Docker">
    <img src="https://img.shields.io/github/last-commit/TechProber/k0s-ansible-provisioner" alt="lastcommit"/>
    <img src="https://custom-icon-badges.herokuapp.com/github/last-commit/TechProber/k0s-ansible-provisioner?logo=history&logoColor=white" alt="lastcommit"/>
</p>

## Introduction

CopyRight 2022 TechProber. All rights reserved.

Maintainers: [ Kevin Yu (@yqlbu) ](https://github.com/yqlbu), [ Shi Kun (@kunish) ](https://github.com/kunish)

This repo serves to provide the end-users a way to provision a Kubernetes Cluster in minutes. Multiple mode are supported, including HA setup.

## Usage

**Provision Cluster**

```bash
ansible-playbook -i ./inventory/single-node.yml provision.yml

```

**Reset Cluster**

```bash
ansible-playbook -i ./inventory/single-node.yml provision.yml
```

## References

- [GitHub - movd/k0s-ansible](https://github.com/movd/k0s-ansible)
- [GitHub Proxy](https://ghproxy.com/)

## License

[MIT (C) TechProber](https://github.com/yqlbu/TechProber/k0s-ansible-provisioner/blob/master/LICENSE)
