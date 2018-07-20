## What is this?
This repository stores the Ansible variables that contain all the credentials needed to run an Open Food Network instance and it's meant to be used from and within https://github.com/openfoodfoundation/ofn-install
## Provisioning
```shell
~/ofn-install $ ansible-playbook playbooks/provision.yml --limit=de-prod -e "@../ofn-de-secrets/production.yml" --ask-vault-pass
```
