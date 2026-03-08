# Personal AWS EKS Jumpbox Provisioner

Ansible playbook to set up an Ubuntu 22.04 VM as a secure access point for AWS EC2/EKS.

### Prerequisites:
- Ansible installation

## Tools Installed
- AWS CLI v2
- kubectl (latest stable)
- k9s (Kubernetes TUI)
- Secure ~/.kube setup (ownership & permissions)

## Usage

```bash
# Dry run
sudo ansible-playbook provision.yaml --check

# Apply
sudo ansible-playbook provision.yaml