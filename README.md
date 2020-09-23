# Ansible role: tmux
Terminal multiplexer, like `screen`.  Multiple, persistent shells.

## Requirements
Only tested on Debian stable, for now.

## Role variables
+ `tmux_extra_cfg`: lines to add to /etc/tmux.conf

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run before removing config from inventory.

## Dependencies
None.

## License
Ansible role licensed [MIT](LICENSE).

## Author Information
Ansible role by [Sean Ho](https://github.com/ho-ansible/)
