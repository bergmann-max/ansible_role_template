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
Add to your `requirements.yml`:

```yaml
roles:
  - name: template
    src: git+ssh://git@github.com/bergmann-max/ansible_role_template.git
    version: main
    scm: git
```

```bash
$ ansible-galaxy install -r requirements.yml
```

## Example Playbook
```yaml
- name: Apply template role
  hosts: all
  become: true

  roles:
    - role: template
      vars:
        example_var: "value"
```

## Tags
| Variable      | Default   | Description                   |
|---------------|-----------|-------------------------------|
| `example_var` | `"value"` | Replace with actual variables |

---

## Handlers
| Variable      | Default   | Description                   |
|---------------|-----------|-------------------------------|
| `example_var` | `"value"` | Replace with actual variables |

## License
Unlicense

## Dependencies
Replace with actual dependencies.

## Author Information
Max Bergmann
