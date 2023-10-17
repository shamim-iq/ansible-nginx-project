# NGINX Server Installation and Configuration Using Ansible

## Overview

This project automates the installation and configuration of the NGINX web server on both virtual machines and containers using Ansible. It provides hands-on experience in orchestrating infrastructure and deploying a common web server across different environments.

## Objectives

- Gain practical familiarity with Ansible playbooks, roles, and inventory management.
- Install and configure NGINX on distinct platforms, understanding the nuances between virtual machines and containers.
- Understand the parallels and differences in managing infrastructure as code for conventional virtual machines and modern containerized environments.

## Table of Contents

- [Environment Setup](#environment-setup)
- [Ansible Playbook Creation](#ansible-playbook-creation)
- [Inventory Definition](#inventory-definition)
- [NGINX Configuration](#nginx-configuration)
- [Testing and Validation](#testing-and-validation)

## Environment Setup

- Install Ansible on your local machine.
- Ensure compatibility with both virtual machines and container platforms.
- Configure SSH access for virtual machines and permissions for managing containers.

## Ansible Playbook Creation

- Create Ansible playbooks for installing and configuring NGINX.
- Define tasks for installing NGINX, managing virtual hosts, configuring SSL (optional), and handling differences between VMs and containers.

## Inventory Definition

- Create inventory files to specify target hosts for VMs.
- Include connection information like IP addresses, SSH credentials.

## NGINX Configuration

- Define configuration templates for NGINX.
- Cover port configurations, virtual host configurations, and other environment-specific settings.
- Handle differences between VMs and containers in the configuration files.

## Testing and Validation

- Execute the Ansible playbooks on the designated hosts using the `ansible-playbook` command.
- Ensure successful installation and proper functionality of NGINX.
- Verify NGINX serves web pages on designated ports.
