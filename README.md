# ansible_role_template

[![Ansible](https://img.shields.io/badge/ansible-%3E%3D%202.10-EE0000?logo=ansible&logoColor=white)](https://www.ansible.com/)
[![Platform](https://img.shields.io/badge/platform-Ubuntu-E95420?logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![your-work](https://img.shields.io/badge/your--work-replace--me-blueviolet?logo=rocket&logoColor=white)](https://shields.io/)
[![License](https://img.shields.io/badge/license-Unlicense-blue)](LICENSE)

An Ansible role template. Replace this with a short description of what the role does.

## Requirements
- Ansible >= 2.10
- foo
- bar

## Role Variables
Variables defaults (`defaults/main.yml`):

| Variable      | Default   | Description                   |
|---------------|-----------|-------------------------------|
| `example_var` | `"value"` | Replace with actual variables |

Variables vars (`vars/main.yml`):

| Variable      | Default   | Description                   |
|---------------|-----------|-------------------------------|
| `example_var` | `"value"` | Replace with actual variables |

## Installation

Include via a `requirements.yml` and install with `ansible-galaxy`:

```yaml
# requirements.yml
- name: template
  src: git+ssh://git@github.com/bergmann-max/ansible_role_template.git
  version: main
```

```bash
ansible-galaxy install -r requirements.yml
```

## Usage

```yaml
- hosts: all
  roles:
    - template
```

## Tags

| Tag  | Description                     |
|------|---------------------------------|
| `foo` | Replace with actual tag info   |
| `bar` | Replace with actual tag info   |

---

## Handlers

| Handler      | Triggered by              |
|--------------|---------------------------|
| `Reload bar` | Replace with actual tasks |

## License
Unlicense

## Dependencies
Replace with actual dependencies.

## Author Information
Max Bergmann
