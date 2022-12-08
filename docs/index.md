# Overview

Project status: **EARLY ALPHA**

This project is still in the experimental stage, and I don't use anything critical on it.

### Hardware

> Still deciding on Hardware

### Features

- [ ] Common applications: Gitea, Paperless, n8n
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

</table>