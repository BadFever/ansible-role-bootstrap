# ansible-role-bootstrap

This ansible role bootstraps systems for configuration management.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

    bootstrap_ansible_user: ansible

The ansible service user.

    bootstrap_ansible_user_password: ""

The ansible service user password.

    bootstrap_ansible_user_ssh_public_key: ""

The ansible service user ssh public key.

    bootstrap_ansible_allow_password_less_sudo: true

Allow passwordless sudo for ansible service user.

## Dependencies

None.

## Example Playbook

    - hosts: all
      role:
        - ansible-role-bootstrap

## License

MIT
