# Architecture

## Implemented baseline
- Endpoint: Windows 11 host (this machine).
- SOC server: Ubuntu Server VM in VirtualBox.

## Networking implemented
- Adapter 1 on Ubuntu VM: NAT (outbound updates and downloads).
- Adapter 2 on Ubuntu VM: Host-only (isolated host to VM lab network).

Evidence:
- screenshots/01_wazuh_running_hostonly_network_created.png
- screenshots/04_ubuntu_vm_network_adapters.png.png
- screenshots/06_ubuntu_ip_check.png
