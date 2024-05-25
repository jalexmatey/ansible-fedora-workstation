# Ansible Fedora Workstation  
  
This playbook installs and configures software that I would like installed on my devices running Fedora Workstation.

## Installation
### Fedora Workstation 40
1. Install Ansible:
    1. `sudo dnf install ansible`
2. Clone or download this repository to your device.
3. Run `ansible-galaxy install -r requirements.yaml`.
4. Run `ansible-playbook fedora_ws_40-playbook.yaml --ask-become-pass`.
