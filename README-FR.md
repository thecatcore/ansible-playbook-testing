# ansible-playbook-testing
Exemple de projet ansible qui déploie une image apache sur un client

## Installation des dépendences

### Paquets (Centos)
```bash
sudo yum install epel-release -y && sudo yum install ansible ansible-lint nano -y
```
## Lancer
```bash
ansible-playbook -i prod.yml deploy.yml
```