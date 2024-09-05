# ansible-playbook-testing
Small example on how to use ansible to deploy an apache image to a client.

## Installing dependencies

### Packages (Centos)
```bash
sudo yum install epel-release -y && sudo yum install ansible ansible-lint nano -y
```
## Launching
```bash
ansible-playbook -i prod.yml deploy.yml
```