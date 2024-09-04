# ansible-playbook-testing
Small example on how to use ansible to deploy an apache image to a client.
Exemple de projet ansible qui déploie une image apache sur un client

## Installation des dépendences

### Paquets (Centos)
```bash
sudo yum install epel-release -y && sudo yum install ansible ansible-lint nano -y
```
### Ansible collections
Une fois le projet cloné, se placer dedans et éxectuer la commande.
```bash
ansible-galaxy collection install -r requirements.yml
```
## Lancer
```bash
ansible-playbook -i prod.yaml deploy.yaml
```