# Ansible Playbook for CTF Environment on Vagrant


## How to use

1. Edit `inventory/inventory.ini` to the hostname that you want to build up
2. Run the below command
   - `ansible-playbook -i inventory/inventory.ini main.yml`

## Roles

- common
- pwn
