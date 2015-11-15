# Ansible Role: nullmailer-mandrill

An Ansible role that installs nullmailer and configures mandrill

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

    nullmailer_mandrill_username
    nullmailer_mandrill_api_key

## Dependencies

- Ginsys.nullmailer - installs nullmailer

## Example Playbook

    - hosts: webservers
      roles:
        - { role: lifeofguenter.nullmailer-mandrill }

## License

MIT