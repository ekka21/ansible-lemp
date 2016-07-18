Ansible LEMP Playbook
This playbook creates a LEMP stack for on Vagrant, and remote servers.

## Prerequisites
- [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)
- [Ansible](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-on-mac-osx)

## Local VM server
- Clone the repo
```
git clone git@github.com:ekka21/ansible-lemp.git
```

- Start up a vagrant VM and provision will run automatically
```
vagrant up
```

- Provisioning our VM
```
cd provision && ansible-playbook main.yml && cd -
```

