# Ansible Role: MariaDB Mirror

Installs the MariaDB mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-mariadb-mirror.git
      name: nexcess.mariadb-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.mariadb-mirror

## License

MIT / BSD
