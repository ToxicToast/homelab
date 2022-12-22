# Overview

Project status: **EARLY ALPHA**

This project is still in the experimental stage, and I don't use anything critical on it.

### Hardware

> Still deciding on Hardware  
> But i want a powerful Server that runs Proxmox or ESXI on it to virtualize at least a Kubernetes Cluster with 2 or 3 Worker Nodes (1 Master - i don't need HA Stuff atm)

> 3x Lenovo M710Q Tiny
> They go up to 32GB Ram (16 might be enough!)
> 128GB SSD which is perfect and they only consume less than 50W (probably 5W on Idle)
> Cheap Tiny Client

### Features

- [ ] Common applications
    - [ ] [Github Runner](https://docs.github.com/en/actions/hosting-your-own-runners)
    - [ ] Paperless
    - [ ] n8n
    - [ ] ioBroker
    - [ ] Node-Red
    - [ ] Home Assistant
    - [ ] MQTT
    - [x] Kafka
    - [ ] Grafana
    - [ ] Prometheus
    - [ ] Elasticsearch
    - [ ] Kibana
    - [x] MySQL
    - [x] Traefik
    - [x] ArgoCD
    - [ ] HashiCorp Vault
- [ ] Automated Kubernetes installation and management
- [ ] Installing and managing applications using Pulumi
- [ ] Automatic rolling upgrade for OS and Kubernetes
- [ ] Automatically update apps
- [ ] Modular architecture, easy to add or remove features/components
- [ ] Automated certificate management
- [ ] Automatically update DNS records for exposed services
- [ ] VPN without port forwarding
- [ ] Expose services to the internet securely with [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/)
- [ ] CI/CD platform (Probably [ArgoCD](https://argoproj.github.io/cd/))
- [ ] Private container registry
- [ ] Distributed storage
- [ ] Support multiple environments (dev, prod)
- [ ] Monitoring and alerting
- [ ] Infrastructure testing

### Services (Own Coded)

- [ ] [Azkaban Gateway](https://api.toxictoast.de)
- [ ] [Home Inventory System](https://inventory.toxictoast.de)
    - [ ] Categories
    - [ ] Items
        - [ ] Locations (where at home is it stored?)
        - [ ] Companies (from which company does it come from?)
        - [ ] Size (what size does it have?)
        - [ ] Type (what type is it? Bottle, Can etc.)
    - [ ] [Shoppinglist](https://shoppinglist.toxictoast.de)
    - [ ] [Discounts](https://discounts.toxictoast.de)
        - [ ] Rewe
        - [ ] Lidl
        - [ ] Aldi
- [ ] [Smartmirror](https://mirror.toxictoast.de)
- [ ] [Twitch Bot](https://twitch.toxictoast.de)
- [ ] [Blog](https://blog.toxictoast.de)
    - [ ] Tags
    - [ ] Posts
    - [ ] Comments
- [ ] [Wow-Raid](https://raid.toxictoast.de)
    - [ ] Guilds
    - [ ] Characters
    - [ ] Raids
    - [ ] Mythic+
    - [ ] Drops

### Tech stack (for now)

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
<tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/k3s/icon/color/k3s-icon-color.svg"></td>
        <td><a href="https://k3s.io">K3s</a></td>
        <td>Lightweight distribution of Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/helm/icon/color/helm-icon-color.svg"></td>
        <td><a href="https://helm.sh">Helm</a></td>
        <td>The Kubernetes package manager</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/argo/icon/color/argo-icon-color.svg"></td>
        <td><a href="https://argoproj.github.io/cd">ArgoCD</a></td>
        <td>GitOps tool built to deploy applications to Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Traefik.logo.png/1200px-Traefik.logo.png"></td>
        <td><a href="https://traefik.io/traefik/">Traefik</a></td>
        <td>The Cloud Native Application Proxy</td>
    </tr>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Apache_kafka.svg/1200px-Apache_kafka.svg.png"></td>
        <td><a href="https://kafka.apache.org">Apache Kafka</a></td>
        <td>Open-source distributed event streaming</td>
    </tr>

</table>