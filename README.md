# Playbooks

My setup for standardized apps across multiple Linux, but mostly Ubuntu installations.

## Setup

To setup your localhost as the ansible main, execute:

```shell
git clone git@github.com:TheGor1lla/ansible-playbooks.git
cd ansible-playbooks
ansible-playbook playbooks/01-host.yml

```

To provision hosts, enter them into a ```inventory/hosts``` file and run:

```shell
ansible-playbook playbooks/<PLAYBOOK.YML> -i inventory/hosts  -u <CLIENT_SSH_USER> 

```


## Don't forget

Activate the ZSH fonts on every terminal
