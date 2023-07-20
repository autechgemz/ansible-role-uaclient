# Ansible Role: uaclient

## Description

Manage Ubuntu Advantage services from Canonical.

## Requirements

None

## Dependencies

None

## OS Platforms

- Ubuntu-20.04
- Ubuntu-22.04

## Example Playbook

```
- hosts: all
  roles:
    - uaclient
```

## Role Variables

### uaclient_debug: (bool)

```
uaclient_debug: false
```

### uaclient_package_ensure: (string)

```
uaclient_package_ensure: 'present'
```

### uaclient_token_handler: (bool)

```
uaclient_token_handler: false
```

### uaclient_token: (string)

```
uaclient_token: ''
```

### uaclient_ua_config_options: (dict)

```
uaclient_config_options: {}
```

## Example vars

```
uaclient_token_handler: true
uaclient_token: 'XXXXXXXXXXXXXXXX'
```
