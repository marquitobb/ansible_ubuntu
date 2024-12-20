# Ansible wt ubuntu

## description

This is a simple ansible playbook to install multiple applications on ubuntu.

### list of applications to be installed

- docker
- docker-compose
- conda
- dbeaver
- postman
- mongodb compass

## run ansible playbook

### install docker

```bash
sudo ansible-playbook -i hosts.ini install_docker.yml --connection=local --ask-become-pass
```

### install conda

```bash
sudo ansible-playbook -i hosts.ini install_conda.yml --connection=local --ask-become-pass
```

### install DBeaver

```bash
sudo ansible-playbook -i hosts.ini install_dbeaver.yml --connection=local --ask-become-pass
```

### install postman

```bash
sudo ansible-playbook -i hosts.ini install_postman.yml --connection=local --ask-become-pass
```

### install mongodb compass

```bash
sudo ansible-playbook -i hosts.ini install_mongodb_compass.yml --connection=local --ask-become-pass
```
