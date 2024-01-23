# import_mysqlDB_role

Ansible role for importing MySQL databases into a server.


## Requirements

- Ansible installed on the local machine.
- A running MySQL server on the target host.

## Role Variables

- `db_password`: MySQL root password.
- `databases`: List of databases to import.
  - Example: `databases: ['db1', 'db2']`


