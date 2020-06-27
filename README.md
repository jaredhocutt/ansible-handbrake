# Handbrake

This role handles installing Handbrake on a Fedora system.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

- `jaredhocutt.rpmfusion`

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.handbrake
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)
