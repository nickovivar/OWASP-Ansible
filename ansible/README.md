# Nix AnsiDock Ansible

## Dependencies

Add dependencies:

```
$ ansible-galaxy install -fr requirements.yml
```


## Prebootstrap

Run prebootstrap:

```
$ ansible-playbook playbooks/prebootstrap.yml -vvv
```
## Bootstrap

Run bootstrap:

```
$ ansible-playbook playbooks/bootstrap.yml -vvv
```
