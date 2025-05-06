# Ansible_Task_NTI

# Install Apache Role for Ansible

An Ansible role for automating the installation and basic configuration of the Apache HTTP Server (httpd) on RedHat Linux systems.

## Overview

This role streamlines the deployment and customization of Apache by:

    Installing the Apache web server.

    Enabling and starting the service.

    Backing up the existing configuration file.

    Changing the default listening port from 80 to 88.

    Opening the new port in the system firewall.

    Configuring SELinux to allow Apache to use the new port.

    Deploying a custom web page to verify functionality.

## Role Structure

The role follows the standard Ansible role directory structure:

```
Install_Apache/
├── defaults/
│   └── main.yml
├── files/
|   └── index.html
├── handlers/
│   └── main.yml
├── meta/
│   └── main.yml
├── tasks/
│   └── main.yml
├── tests/
│   └── test.yml
├── vars/
│   └── main.yml
└── .travis.yml
```
