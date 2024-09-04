# ansible-playbook-testing

## Installing dependencies

### Packages (Centos)
```bash
sudo yum install epel-release -y && sudo yum install ansible ansible-lint nano -y
```
### Ansible collections
```bash
ansible-galaxy collection install -r requirements.yml
```
## Launching
```bash
ansible-playbook -i prod.yaml deploy.yaml
```