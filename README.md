# ansible-apps_consul_agent

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_consul_agent-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_consul_agent.svg)](https://github.com/lotusnoir/ansible-apps_consul_agent/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_consul_agent?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent)
[![downloads](https://img.shields.io/ansible/role/d/56915)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56915)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure consul agent

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_consul_agent
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_consul_agent


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
