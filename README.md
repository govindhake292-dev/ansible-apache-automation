# Automated Apache Web Server Deployment Using Ansible

## Project Overview

This project automates the installation and configuration of Apache HTTP Server on RHEL 8 using Ansible.

## Technologies Used

* Linux (RHEL 8)
* Ansible
* Apache HTTP Server
* SSH
* VMware Workstation

## Project Architecture

Control Node (Ansible Server)
|
| SSH
|
Managed Node (RHEL 8)
|
Apache HTTP Server

## Features

* Automated Apache Installation
* Automated Service Start
* Automated Service Enablement
* Infrastructure Automation

## Inventory File

The inventory file contains the IP address of the managed node.

## Playbook Execution

Run the playbook using:

ansible-playbook -i inventory install_httpd.yml

## Verification

Check Apache status:

systemctl status httpd

Open website:

http://SERVER_IP

## Skills Learned

* Linux Administration
* Ansible Automation
* YAML
* Apache Web Server
* SSH Configuration
* Infrastructure Automation
* DevOps Fundamentals

## Author

Govind Hake
