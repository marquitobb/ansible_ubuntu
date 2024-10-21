# Ansible wt ubuntu

## description

This is a simple ansible playbook to install multiple applications on ubuntu.

### list of applications to be installed

- docker
- docker-compose
- git

## run ansible playbook

### install docker

```bash
sudo ansible-playbook -i hosts.ini install_docker.yml --connection=local --ask-become-pass
```

### install conda

```bash
sudo ansible-playbook -i hosts.ini install_conda.yml --connection=local --ask-become-pass
```