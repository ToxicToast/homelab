# Terraform

[![tag](https://img.shields.io/github/v/tag/toxictoast/IaC?style=flat-square&logo=semver&logoColor=white)](https://github.com/toxictoast/IaC/tags)

Service status: **ALPHA**

This service is still in development. Expect Things to break.


This is my main.tf File with only the required provider for Proxmox, since every VM runs on a Proxmox Hypervisor

```yaml
 terraform {
   required_version = ">= 1.3.0"

   required_providers {
     proxmox = {
       source = "telmate/proxmox"
       version = "2.9.11"
     }
   }
 }
```