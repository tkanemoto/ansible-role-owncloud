# Ansible Role: ownCloud

Installs ownCloud for Debian/Ubuntu linux machines. Uses PostgreSQL.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    owncloud_database_db: owncloud

The name of the database to create.

    owncloud_database_username: owncloud

The database user name.

    owncloud_database_password: s3cr1t

The database password.

## Example Playbook (using default config)

    - hosts: webservers
      roles:
        - tkanemoto.owncloud

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Takeshi Kanemoto](https://tkanemoto.com/).