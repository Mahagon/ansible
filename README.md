# Ansible Playbooks

This repository contains Ansible playbooks to install and configure local CachyOS environments.

## Getting Started

To get started with these playbooks, you'll need to have some requirements installed on your system.

```shell
paru -S ansible git
```

## Usage

Each playbook is designed to perform specific tasks. You can run them using the `ansible-playbook` command.

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory playbook-gaming.yml -e "username=$USER" --ask-become-pass
```

## Contributing

Contributions are welcome! Please submit a pull request or open an issue if you have any suggestions or improvements.
