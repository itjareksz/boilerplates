# Ansible playbook boilerplate

## Values to change

Change values in `inventory.yml` before running playbook.

## Usage

Run playbook with command:

```bash
ansible-playbook <playbook_name.yml> --ask-become-pass
```

- `--ask-become-pass` - show prompt to input password for privilage escalation method (`sudo` or `su` used on target machine)
