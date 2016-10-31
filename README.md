# ansible-maint
Ansible playbooks to manage general daily maintenance tasks

## Purpose
To provide a unified automation platform to deploy new baremetal servers, deploy SSH users, and all OS-level configs


## How to Use
Replace the example files provided in `group_vars` and `host_vars` with server and user details. Execute the deploy playbook as follows:

```
ansible-playbook Deploy-Maint-Tasks.yml -i inventory.yml
```


