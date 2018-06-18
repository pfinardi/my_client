# Configure your own Ubuntu Linux Client with Ansible


---
## SetUp

### Ansible

Ansible installation:
```
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

### Repo Git

Clone repo:

```
git clone git@github.com:pfinardi/my_client.git
```

then
```
cd my_client
```

### Variables

Copy template for "all" variables:
```
cp group_vars/all_template group_vars/all
```

then set all variables in **group_vars/all**


### Start

```
ansible-playbook local.yml
```
