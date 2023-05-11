# Ansible Runbook: backup_minecraft

[![Build](https://github.com/dcjulian29/ansible-runbook-backup_minecraft/actions/workflows/build.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-backup_minecraft/actions/workflows/build.yml) [![Release](https://github.com/dcjulian29/ansible-runbook-backup_minecraft/actions/workflows/release.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-backup_minecraft/actions/workflows/release.yml) [![GitHub Release](https://img.shields.io/github/v/release/dcjulian29/ansible-runbook-backup_minecraft)](https://github.com/dcjulian29/ansible-runbook-backup_minecraft/releases) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-runbook-backup_minecraft.svg)](https://github.com/dcjulian29/ansible-runbook-backup_minecraft/issues)

This an Ansible runbook that will backup a Minecraft server deployed with my role.

## Requirements

- Internet Connection

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
collections:
- name: dcjulian29.backup_minecraft
  type: git
  source: https://github.com/dcjulian29/ansible-runbook-backup_minecraft.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy collection install -r requirements.yml
```

To excute the runbook:

```shell
ansible-playbook dcjulian29.backup_minecraft.runbook.yml
```
