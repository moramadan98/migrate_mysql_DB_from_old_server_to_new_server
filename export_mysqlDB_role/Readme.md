# export_mysqlDB_role

Ansible role for exporting MySQL databases and copying them from a remote server to the local machine.

## Requirements

- Ansible installed on the local machine.
- A running MySQL server on the target host.

## Role Variables

- `db_password`: MySQL root password.
- `databases`: List of databases to export.

