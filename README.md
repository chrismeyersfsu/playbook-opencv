# playbook-opencv
Ansible playbook to install opencv on a raspberry pi.
```
ansible-playbook -i pi.yml -vvvv
```
Set your pi ip address(es) in `pis.yml` and update `group_vars/pis.yml` with your pi login / password.

**Note:** The `make` command will take **HOURS** to run. Please be patient.
