ansible-dropbox
===============

Ansible playbook to install Dropbox in Linux

Supported distributions:

- Fedora
- CentOS
- Ubuntu

Setup
-----

```sh
$ git clone https://github.com/dceoy/ansible-dropbox.git
$ cd ansible-dropbox
$ cp example_hosts hosts
$ vim hosts       # => edit
```

Usage
-----

Install Dropbox

```sh
$ ansible-playbook -i hosts install.yml
```
