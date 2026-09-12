# Security Overview

This public showcase is separated from the private production implementation.

## Public repository excludes

- Zabbix API tokens
- vCenter credentials
- real internal IP addresses and hostnames
- production site configuration
- company topology
- private incident data
- production logs
- secret-bearing environment files
- internal automation details that should remain private

## Production safety principles

- credentials live outside source control
- sensitive actions are approval-gated
- AI context is filtered before remote submission
- monitoring remains available when AI is degraded
- action success is followed by independent verification
- operator actions and outcomes are auditable