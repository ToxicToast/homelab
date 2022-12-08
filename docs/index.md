# ToxicToast's Homelab

**[Features](#features) • [Documentation](https://homelab.toxictoast.de)**

[![tag](https://img.shields.io/github/v/tag/toxictoast/ToxicTV?style=flat-square&logo=semver&logoColor=white)](https://github.com/toxictoast/ToxicTV/tags)
[![tag](https://img.shields.io/github/v/tag/toxictoast/IaC?style=flat-square&logo=semver&logoColor=white)](https://github.com/toxictoast/IaC/tags)
[![tag](https://img.shields.io/github/v/tag/toxictoast/homelab?style=flat-square&logo=semver&logoColor=white)](https://github.com/toxictoast/homelab/tags)
[![document](https://img.shields.io/website?label=document&logo=gitbook&logoColor=white&style=flat-square&url=https%3A%2F%2Fhomelab.toxictoast.de)](https://homelab.toxictoast.de)


This project utilizes [Infrastructure as Code](https://en.wikipedia.org/wiki/Infrastructure_as_code) with [Pulumi](https://www.pulumi.com) to automate provisioning a K3S Cluster and updating self-hosted services in my homelab. 

> **What is a homelab?**
>
> Homelab is a laboratory at home where you can self-host, experiment with new technologies, practice for certifications, and so on.
> For more information about homelab in general, see the [r/homelab introduction](https://www.reddit.com/r/homelab/wiki/introduction).

## Overview

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


### Tech stack (for now)

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/argo/icon/color/argo-icon-color.svg"></td>
        <td><a href="https://argoproj.github.io/cd">ArgoCD</a></td>
        <td>GitOps tool built to deploy applications to Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Docker</a></td>
        <td>Ephemeral PXE server and convenient tools container</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/helm/icon/color/helm-icon-color.svg"></td>
        <td><a href="https://helm.sh">Helm</a></td>
        <td>The package manager for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/k3s/icon/color/k3s-icon-color.svg"></td>
        <td><a href="https://k3s.io">K3s</a></td>
        <td>Lightweight distribution of Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/kubernetes/icon/color/kubernetes-icon-color.svg"></td>
        <td><a href="https://kubernetes.io">Kubernetes</a></td>
        <td>Container-orchestration system, the backbone of this project</td>
    </tr>
</table>