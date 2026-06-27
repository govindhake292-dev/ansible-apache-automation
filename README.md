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


## Screenshots

### Ansible Connection Test

![Connection](screenshots/Connection.png)

### Playbook Execution

![Playbook](screenshots/playbook.png)

### Apache Service Status

![Apache Status](screenshots/Apachestatus.png)

### Website Output

![Website](screenshots/Website.png)

## Project Demo Video

[Click here to watch demo](https://github.com/govindhake292-dev/ansible-apache-automation/raw/main/ansible-demo.mp4.mp4)

## Author

Govind Hake
