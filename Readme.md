# MySQL Database Migration Playbook

This Ansible playbook automates the process of exporting MySQL databases from an old server and importing them into a new server.

## Before Use

Ensure that you have SSH connection to both the old server and the new server.

## Playbook Overview

The playbook consists of two main tasks: exporting databases from the old server and importing them into the new server.




## Inventory

Add ips for old and new servers

## example

```ini
[old-server]
## old-server-ip

[new-server]
## new-server-ip