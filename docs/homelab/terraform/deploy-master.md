# Deploy the Master VM

```yaml
resource "proxmox_vm_qemu" "k3s-master" {
  name = "k3s-master"
  desc = "Kubernetes Master Node"
  vmid = "100"
  target_node = "pve"
  agent = 1
  clone = var.proxmox_clone_name
  cores = 1
  sockets = 2
  memory = 2048

  network {
    bridge = "vmbr0"
    model = "virtio"
  }

  disk {
    storage = "local"
    type = "scsi0"
    size = "50G"
  }

  os_type = "cloud-init"
  ipconfig0 = "ip=192.168.1.150,gw=192.168.1.1"
  nameserver = "192.168.1.1"
}
```