# ansible-nginx-worker-setup
Playbook to install and configure NGINX on worker node


# Ansible Tower: NGINX Setup

Ansible playbook to install and configure NGINX on a worker node via Ansible Tower.

## Inventory Format
- Inventory is located at: `inventories/hosts.ini`

## Playbook Execution

```bash
ansible-playbook -i inventories/hosts.ini playbook.yml

