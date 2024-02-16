# Playbooks description
## klnagent.yaml
Install/Reinstall only agent

## kesl.yaml
Install/Reinstall only kesl

## delete.yaml 
Delete Kesl and KLNagent

# hosts.yaml
List of hosts to work with

# Usage
```bash
ansible-play <yaml file> -i hosts.yaml [--ask-pass]
```