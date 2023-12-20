# Ansible playbooks for aws linux OS

## Installing ansible
- requires python3 (should be pre-installed on the ami)
- requires pip3 -> install via terraform or manually via `yum install python3-pip`
- install ansible via pip: `pip3 install ansible`

## Local playbook usage

- copy the playbook onto the machine you want to provision
- run the playbook using: `ansible-playbook playbook.yaml`
