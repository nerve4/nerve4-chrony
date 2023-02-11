# Chrony

An Ansible role that installs Chrony to CENTOS 7 and Ubuntu. More info about Chrony: [link](https://chrony.tuxfamily.org/)

## Requirements

Make sure, you made your vars file with valid path to custom template or you can use Default vars.

You need `ansible 2.13.7` to run this module

## Tasks descriptions

- main.yml - Run the OS check and run the relevant playbook
- rhel.yml - Install Chrony on RHel 7.x
- ubuntu.yml - Install Chrony on Ubuntu

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- hosts: servergroup
  become: true
  become_user: lee

  vars_files:
    - vars/main.yml
    
  roles:
    - nerve4-chrony
```

## Maintainer Information
Lee | 2023