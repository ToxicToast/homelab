# Overview

Project status: **EARLY ALPHA**

This project is still in the experimental stage, and I don't use anything critical on it.

### Hardware

> Still deciding on Hardware  
> But i want a powerful Server that runs Proxmox or ESXI on it to virtualize at least a Kubernetes Cluster with 2 or 3 Worker Nodes (1 Master - i don't need HA Stuff atm)

> 2 or 3x Lenovo M710Q Tiny
> They go up to 32GB Ram (16 might be enough but i will go for 32 for proxmox!)
> 128GB SSD which is perfect and they only consume less than 50W (probably 5W on Idle)
> Cheap Tiny Client
> 
> Will use one for [OPNSense](https://opnsense.org)
 

### Features

- [ ] Common applications
    - [ ] [Github Runner](https://docs.github.com/en/actions/hosting-your-own-runners)
    - [ ] paperless-ngx
    - [ ] n8n
    - [ ] ioBroker
    - [ ] Node-Red
    - [ ] Home Assistant
    - [ ] MQTT
    - [ ] Kafka
    - [ ] Grafana
    - [x] Prometheus
    - [ ] Elasticsearch
    - [ ] Kibana
    - [x] MySQL / MariaDB
    - [x] [Traefik](https://traefik.thoraxia.de)
    - [x] [ArgoCD](https://argocd.thoraxia.de)
    - [ ] HashiCorp Vault
    - [ ] Memos or HedgeDoc or Documize or Docusaurus (still deciding)
    - [ ] Shiori
    - [ ] Kutt
    - [ ] Vikunja
    - [ ] Tekton
    - [x] Uptime Kuma
- [x] Automated Kubernetes installation
- [ ] Installing and managing applications using GitOps
- [ ] Automatic rolling upgrade for OS and Kubernetes
- [ ] Automatically update apps
- [ ] Modular architecture, easy to add or remove features/components
- [ ] Automated certificate management
- [ ] Automatically update DNS records for exposed services
- [ ] VPN without port forwarding
- [ ] Expose services to the internet securely with [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/)
- [ ] CI/CD platform
    - [x] ArgoCD
    - [ ] Tekton
- [ ] Private container registry
- [ ] Distributed storage
- [ ] Support multiple environments (dev, prod)
- [ ] Monitoring and alerting
- [ ] Infrastructure testing

### Services (Own Coded)

- [ ] [Azkaban Gateway](https://api.thoraxia.de)
- [ ] [Authentication](https://auth.thoraxia.de)
- [ ] [Home Inventory System](https://inventory.thoraxia.de)
    - [ ] [Categories](https://inventory.thoraxia.de/category)
    - [ ] [Items](https://inventory.thoraxia.de/item)
        - [ ] [Locations](https://inventory.thoraxia.de/item/location/{locationId}) (where at home is it stored?)
        - [ ] [Companies](https://inventory.thoraxia.de/item/company/{companyId}) (from which company does it come from?)
        - [ ] [Sizes](https://inventory.thoraxia.de/item/size/{sizeId}) (what size does it have?)
        - [ ] [Types](https://inventory.thoraxia.de/item/type/{typeId}) (what type is it? Bottle, Can etc.)
    - [ ] [Location](https://inventory.thoraxia.de/location)
    - [ ] [Company](https://inventory.thoraxia.de/company)
    - [ ] [Size](https://inventory.thoraxia.de/size)
    - [ ] [Type](https://inventory.thoraxia.de/type)
    - [ ] [Shoppinglist](https://shoppinglist.thoraxia.de)
    - [ ] [Discounts](https://discounts.thoraxia.de)
        - [ ] Rewe
        - [ ] Lidl
        - [ ] Aldi
- [ ] [Smartmirror](https://mirror.thoraxia.de)
- [ ] Twitch
    - [ ] [Bot](https://twitchbot.thoraxia.de)
    - [ ] [Events](https://twitchevents.thoraxia.de)
    - [ ] Commands
- [ ] [Blog](https://blog.thoraxia.de)
    - [ ] Tags
    - [ ] Posts
    - [ ] Comments
- [ ] [Wow-Raid](https://raid.thoraxia.de)
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
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/metal3/icon/color/metal3-icon-color.svg"></td>
        <td><a href="https://metal3.io">Metal3</a></td>
        <td>Bare metal host provisioning for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Traefik.logo.png/1200px-Traefik.logo.png"></td>
        <td><a href="https://traefik.io/traefik/">Traefik</a></td>
        <td>The Cloud Native Application Proxy</td>
    </tr>

</table>