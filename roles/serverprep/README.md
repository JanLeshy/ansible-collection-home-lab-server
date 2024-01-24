# Role Name

A brief description of the role goes here.

## Requirements

root access to the servers, for installing sudo, after that, sudo access for the user running the playbook.

## Role Variables

| Name                   | Default Value | Description                                                                                                  |
| ---------------------- | ------------- | ------------------------------------------------------------------------------------------------------------ |
| `timezone`             | Europe/Berlin | The server timezone, availabe timezones [here](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) |
| `installing_sudo`      | true          | If true sudo will be installed [additional infos](https://wiki.debian.org/sudo/)                             |
| `ufw_additional_rules` | none          | define additional rules, als an dict example - { rule: allow, port: 443, proto: tcp }                                         **ATTENTION**: the SSH port 22 will allow per default |
| `variable4`            |               |                                                                                                              |

## Dependencies

none

## Example Playbook

## License

MIT

## Author Information

Jan Roepke (JanLeshy)
have fun with it, and feel free to contribute or contact me.
