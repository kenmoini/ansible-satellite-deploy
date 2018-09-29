# ansible-satellite-deploy
Deploy a single Red Hat Satellite 6.4 Beta Server using Ansible!
Set a few variables, kick back, and get some reposyncing quickly!

## Requirements
Requirements to get this to fly

### Client
* make
* ansible 2.6

### Target
* Red Hat Enterprise Linux >= 7.3
* Red Hat Satellite/Smart Management Subscription

## Run it

### Prepare
```bash
$ git clone https://github.com/kenmoini/ansible-satellite-deploy.git
$ cd ansible-satellite-deploy
```

Edit *vars.yml* to reflect your settings, most notably...
```yaml
---
ansible_ssh_host: 10.1.2.10
rhn_username: yourrhnuser
rhn_password: yourrhnpass
```
...and anything else that says <REPLACE_ME>

### Execute
```bash
$ make
```

## Meanwhile
Coffee time!

