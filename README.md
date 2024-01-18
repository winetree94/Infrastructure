# Deployment

```bash
infisical run -- ansible-playbook ./playbook/site.yml -i ./inventory/inventory.yml
```

# Copy configs

```bash
scp root@10.132.246.1:~/.kube/config ~/.kube/config -i ./cluster.key
```

# Reboot

```bash
infisical run -- ansible-playbook ./playbook/reboot.yml -i ./inventory/inventory.yml
```

# Reset

```bash
infisical run -- ansible-playbook ./playbook/reset.yml -i ./inventory/inventory.yml
```