### droppedasbaby

hi. yes, i was metaphorically dropped. frequently.

software engineer at [affirm](https://www.affirm.com). previously [spare labs](https://www.sparelabs.com) and [ualberta](https://www.ualberta.ca). i build distributed systems professionally and run them at home for fun.

## The Homelab

3 mini PCs running an 80+ pod [kubernetes](https://kubernetes.io) cluster that processes 6TB/month. 14 minutes to provision, 2 minutes to destroy. started with 1 dusty PC and [ubuntu](https://ubuntu.com). it escalated.

- [proxmox](https://www.proxmox.com) + [talos linux](https://www.talos.dev) + [terraform](https://www.terraform.io) (migrating to [pulumi](https://www.pulumi.com))
- sharded [mongodb](https://www.mongodb.com) (3x shards, 3x config servers, 3x mongos routers)
- [longhorn](https://longhorn.io) distributed storage across 3 nodes
- gitops with [flux](https://fluxcd.io), [kyverno](https://kyverno.io) policy engine
- 3-10x scraper pods, 10x self-resurrecting vpn pods
- [prometheus](https://prometheus.io) + [grafana](https://grafana.com) + [loki](https://grafana.com/oss/loki/) observability stack

## What I Work With

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?style=flat&logo=pulumi&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

## Elsewhere

- blog: [droppedasbaby.com](https://www.droppedasbaby.com)
- instagram: [@droppedasbaby](https://www.instagram.com/droppedasbaby)
