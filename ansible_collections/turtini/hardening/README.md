# turtini.hardening

Hardening and compliance automation for public sector and regulated environments.

The `turtini.hardening` collection provides reference-grade Ansible content aligned with
DISA STIGs, FIPS expectations, and operational best practices. The focus is on clarity,
safety, and explicit operator intent rather than one-click hardening.

This collection is designed for:
- public sector environments
- regulated or audited systems
- teams that require explainable, reviewable automation

---

## Design principles

- **Clarity over cleverness**  
  Tasks are written to be readable and auditable.

- **Safe-by-default behavior**  
  No disruptive changes are made without explicit opt-in.

- **Reference implementations**  
  These roles demonstrate *how* controls can be implemented, not a claim of blanket compliance.

- **Composable usage**  
  Roles are intended to be consumed selectively and integrated into larger workflows.

---

## Included content

### Roles

- **`stig_rhel9`**  
  Reference implementation of selected DISA STIG-aligned controls for Red Hat Enterprise Linux 9.

---

## Requirements

- Ansible Core 2.14 or newer
- Supported platforms are documented per role

---

## Installation

Install from Ansible Galaxy:

```bash
ansible-galaxy collection install turtini.hardening

