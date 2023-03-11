# Ansible playbooks for IDCF Cloud

```console
$ ansible -i inventories/dev/hosts.ini -m ping all
```

```console
$ ansible-playbook -i inventories/dev/hosts.ini playbooks/site.yml --extra-vars="{ "update_os_packages": true }" --ask-vault-pass
```
