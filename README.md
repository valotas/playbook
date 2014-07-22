# Personal Ansible playbook
Just a bunch of recipies to help be setup my dev environment

## Installation
You are going to need git and ansible. So in order to get started, do the following

```
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible git
```

and then in order to install this repo

```
git clone git@github.com:valotas/playbook.git ~/.ansible
cd ~/.ansible
./play vim.yml
```
