# Ansible-Role: pptpd-Deamon

I use this playbook to setup quickly a pptpd-server with ansible.

Tested with Ubuntu 13.04 x64

## Run

Set the **username**/**password** in ```vars.yml``` and Run:

```bash
ANSIBLE_HOSTS=<server-ip>, ansible-playbook vpn.yml
```