# Ansible Vagrant LAMP Project

This project automates the deployment of a complete LAMP stack environment using Ansible and Vagrant.

## Features

- Creates an Ubuntu virtual machine using Vagrant
- Installs Apache web server
- Installs MySQL server
- Installs PHP and PHP-MySQL module
- Configures UFW firewall
- Uses Ansible roles for organized deployment
- Runs everything from a single Ansible playbook

## Technologies Used

- Ansible
- Vagrant
- Ubuntu
- Apache
- MySQL
- PHP
- UFW
- VirtualBox

## Project Structure

```bash
ansible-lamp/
├── inventory/
├── roles/
│   ├── apache/
│   ├── mysql/
│   ├── php/
│   └── firewall/
├── site.yml
└── Vagrantfile


How to run :
vagrant up
ansible-playbook -i inventory/hosts site.yml
