# ansible-apps_consul_agent_windows

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_consul_agent_windows-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent_windows)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_consul_agent_windows.svg)](https://github.com/lotusnoir/ansible-apps_consul_agent_windows/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_consul_agent_windows?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent_windows)
[![downloads](https://img.shields.io/ansible/role/d/61804)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent_windows)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/61804)](https://galaxy.ansible.com/lotusnoir/apps_consul_agent_windows)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure consul agent on windows
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_consul_agent_windows
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_consul_agent_windows


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
