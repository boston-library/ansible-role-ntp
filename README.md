# ansible-ntp

An Ansible role for installing NTP.

## Role Variables

- `ntp_version` - NTP version
- `ntp_servers` - A list of NTP servers to use (default: `*.ubuntu.pool.ntp.org`)

## Reference

This ansible role is taken mostly out of [ansible-ntp](https://github.com/azavea/ansible-ntp.git) from Azavea Inc., but I stripped it down for brevity.