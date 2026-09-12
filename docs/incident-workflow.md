# Incident Workflow

```text
Monitoring / Virtualization / Network Signal
                 ↓
        Normalize the evidence
                 ↓
         Correlate related events
                 ↓
      Classify likely root cause
                 ↓
       Generate operator playbook
                 ↓
     Human approval if sensitive
                 ↓
            Execute action
                 ↓
         Verify system recovery
                 ↓
          Record audit outcome
```

## Why verification matters

A command returning successfully does not prove the incident is resolved. OpsPilot treats post-action verification as a separate operational step.

## Why approvals matter

Actions that can materially change production infrastructure should not be silently executed by an AI system. The platform separates analysis/recommendation from sensitive execution.