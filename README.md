hi. yes, i was metaphorically dropped. frequently.

software engineer at [affirm](https://www.affirm.com). previously [spare labs](https://www.sparelabs.com) and [ualberta](https://www.ualberta.ca). i build distributed systems professionally and run them at home for fun.

## the homelab

3 mini PCs running an 80+ pod [kubernetes](https://kubernetes.io) cluster that processes 6TB/month. 14 minutes to provision, 2 minutes to destroy. started with 1 dusty PC and [ubuntu](https://ubuntu.com). it escalated.

- [proxmox](https://www.proxmox.com) + [talos linux](https://www.talos.dev) + [terraform](https://www.terraform.io) (migrating to [pulumi](https://www.pulumi.com))
- sharded [mongodb](https://www.mongodb.com) (3x shards, 3x config servers, 3x mongos routers)
- [longhorn](https://longhorn.io) distributed storage across 3 nodes
- gitops with [flux](https://fluxcd.io), [kyverno](https://kyverno.io) policy engine
- 3-10x scraper pods, 10x self-resurrecting vpn pods
- [prometheus](https://prometheus.io) + [grafana](https://grafana.com) + [loki](https://grafana.com/oss/loki/) observability stack

## what i work with

go · python · typescript · terraform · pulumi · kubernetes · docker

## elsewhere

- blog: [droppedasbaby.com](https://www.droppedasbaby.com)
- instagram: [@droppedasbaby](https://www.instagram.com/droppedasbaby)
