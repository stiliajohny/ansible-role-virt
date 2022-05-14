# ansible-role-virt

Install and configure virtualisation software

## Requirements

N/A

## Role Variables

```yaml
docker_images:
  - alpine
  - amazonlinux
  etc

  users:
  - name: foo

```

## Dependencies

N/A

# Example Playbook

---

```yaml
- hosts: servers
  roles:
    - { role: ansible-role-virt }
```

## License

GPLv3

## Author Information

John Stilia - stilia.johny@gmail.com
