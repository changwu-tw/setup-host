# Setup host

Setup a server with basic requirement

## Requirements

A clean Server with a public IP

```
$ apt-get install python-minimal aptitude
```

## Install Ansible on your Local

Once you have installed Ansible, you can setup a host with:

1. Installl common library
2. Add a new user account
3. Disable ssh login
4. Basic firewall
5. Timezone setting
6. python dev environment

## Set variables

Modify the variables in `provision.yml` with your settings

## Run Playbooks 

```
$ ansible-playbook provision.yml
```
