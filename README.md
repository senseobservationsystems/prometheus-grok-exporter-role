# Ansible Role: prometheus-grok-exporter

An Ansible role that installs Prometheus Grok Exporter on Ubuntu|Debian|Redhat-based machines with systemd|Upstart|sysvinit.

## Requirements

All needed packages will be installed with this role.

## Role Variables

Available variables are listed below, along with default values:
```yaml
```
## Dependencies

- UnderGreen.prometheus-exporters-common

## Example Playbook
```yaml
- hosts: grok
  roles:
    - prometheus-grok-exporter
```
## License

GPLv2
