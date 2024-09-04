# ansible-playbook-testing

## Installing dependencies

### Packages (Centos)
`sudo yum install epel-release -y && sudo yum install ansible ansible-lint nano -y`
### Ansible collections
`ansible-galaxy collection install -r requirements.yml`
## Launching
`ansible-playbook -i prod.yaml deploy.yaml`