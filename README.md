# argon-one

Ansible Role for configuring a Raspberry Pi for use in an Argon One case. This role installs the power button and fan control for the HAT inside the [Argon One](https://www.argon40.com/argon-one-raspberry-pi-4-case.html) Raspberry Pi 4 case.

- - http://wagnerstechtalk.com/argonone/#Install_Argon_ONE_Scripts_in_Pi_OS_3264-bit
## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
    - hosts: all
      roles:
         - agarthetiger.argon-one
```

## License

MIT

## Author Information

Andrew Garner (@agarthetiger)