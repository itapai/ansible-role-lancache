# Ansible Role: Lancache

Install [Lancache](https://lancache.net) using Docker.

## Requirements

The only real dependency for this role is [docker](https://community.docker.com/).
This role takes care of installing docker if it is not already installed.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

- community.docker
- geerlingguy.pip
- geerlingguy.docker

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - itapai.lancache

## License

MIT
