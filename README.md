# Ansible

### Copy SSH Key

ssh-copy-id -i ~/.ssh/mykey user@host

### Install common software

`ansible-playbook -i inventory.yaml playbooks/common.yaml`

### Apply dotfiles

Source: https://github.com/hashdot/dotfiles

`ansible-playbok -i inventory.yaml playbooks/dotfiles.yaml`
