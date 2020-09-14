# Ansible role: tmux
Ansible role for terminal multiplexer

## Requirements
Only tested on Debian stable, for now.

## Role variables
+ `tmux_extra_cfg`: lines to add to /etc/tmux.conf

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run before removing config from inventory.

## License
Ansible role licensed [MIT](LICENSE).

## Author
Ansible role by [Sean Ho](https://github.com/ho-ansible/)
