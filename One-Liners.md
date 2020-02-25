## Ansible One-Liners
#### List host groups
ansible localhost -m debug -a "var=groups.keys()"
