# ansible-bacula-sd-server
bacula SD server

## Test with Vagrant

```console
ansible-playbook -v -i .inventory-vagrant playbooks/debian/bacula-sd-debian-server.yaml --ask-vault-pass
```

## Run

```console
ansible-playbook -v -i .inventory playbooks/debian/bacula-sd-debian-server.yaml --ask-vault-pass
```