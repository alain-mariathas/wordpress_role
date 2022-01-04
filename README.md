Ansible Role: wordpress

Requirements : docker

Supported distributions:

    ubuntu

This role installs docker and docker_container ansible module.

Example playbook

```yml
---
- name: "Wordpress into container"
  hosts: prod
  become: true
  roles:
    - docker_role
    - wordpress_role
```
