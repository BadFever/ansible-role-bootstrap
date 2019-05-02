# ansible-role-bootstrap

[![Build Status](https://travis-ci.org/BadFever/ansible-role-bootstrap.svg?branch=master)](https://travis-ci.org/BadFever/ansible-role-bootstrap)

This ansible roles bootstraps all servers used within ansible configuration management.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

The ansible service user.

```yaml
ansible_user: ansible
```

The ansible service user password:

```yaml
ansible_user_password: "ansible"
```

The ansible service user ssh public key.

```yaml
ansible_user_ssh_public_key: ""
```

Allow passwordless sudo for ansible service user.

```yaml
allow_password_less_sudo: true
```

## Dependencies

None.

## Example Playbook

```YAML
- hosts: all
  role:
    - ansible-role-bootstrap
```

## License

MIT
