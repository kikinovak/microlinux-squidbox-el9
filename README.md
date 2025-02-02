# microlinux-squidbox-el9

Éditer `/root/.ansible.cfg` :

```
[defaults]
vault_password_file = /etc/ansible_vault_pass
```

Renseigner le mot de passe dans `/etc/ansible/vault_pass`, puis :

```
# chmod 0400 /etc/ansible/vault_pass
```

