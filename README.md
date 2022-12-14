# infra-runbook
Homelab infrastructure and configs

Centralized documentation for my homelab, servers, and network infrastructure. At a high level I am running 4x Proxmox servers in a cluster, 1x standalone Proxmox server, 1x Arch desktop, 1x Arch laptop, 1x Arch dedicatesd server (Hetzner, DE), and 1x Debian dedicated server (Canada, OVH). Specifications for each can be found here. 

Build a ventoy usb disk https://www.ventoy.net/en/index.html, this will allow you to have multiple bootable ISOs on a single usb disk. I would have killed for this when I was a PC tech and building desktops and laptops with different OSs. 

On this disk, download the following:
- Windows 10/11 -> 
- Arch Linux -> 
- Proxmox -> 

Proxmox Hosts
- Boot to the Proxmox ISO and run through the installer. I use a logical naming convention for my hosts (vm101-1xx) for servers taht will join the cluster. 
- After installed, go to this website https://tteck.github.io/Proxmox/ - find the helper script for ``Proxmox VE 7 Post Install`` and run it. This will update the system, but more importantly remove the Enterprise licensing repositories and add the community repositories. This will be 
