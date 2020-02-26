## Ansible One-Liners
#### List host groups
ansible localhost -m debug -a "var=groups.keys()"
#### Get uname information
ansible localhost -b -m shell -a "uname -a"
