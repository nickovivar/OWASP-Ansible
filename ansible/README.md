# Nix AnsiDock Ansible

## Dependencies

Add dependencies:

```
$ ansible-galaxy install -fr requirements.yml
```

## Initial Access for CloudCone

Run initial-access:

```
$ ansible-playbook playbooks/initial-access.yml --ask-pass
```
Run the playbook with the password provide by Cloud Cone.

## Prebootstrap

Run prebootstrap:

```
$ ansible-playbook playbooks/prebootstrap.yml
```
## Bootstrap

Run bootstrap:

```
$ ansible-playbook playbooks/bootstrap.yml
```

## Install Nix Package Manager

Run nix-install:

```
$ ansible-playbook playbooks/nix-install.yml
```

