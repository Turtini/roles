# turtini.stig_rhel9
Reference Ansible role implementing selected DISA STIG controls for RHEL 9

## Purpose

This project provides a **reference implementation** of selected DISA STIG-aligned configuration changes for **RHEL 9**.
It is intended to accelerate compliance efforts and should be **reviewed and tailored** to each environment.

This repository is **not** an official Red Hat or DISA deliverable.

## Scope

- Target OS: RHEL 9
- Approach: safe-by-default tasks with explicit opt-ins for higher-impact controls
- Designed for: repeatable hardening + future audit evidence output

## Usage (early draft)

> Coming soon. Initial commits focus on role structure and preflight safety checks.

## Safety & Design Principles

- Preflight checks validate OS/version and execution prerequisites
- Changes are scoped, tagged, and readable
- Default behavior avoids high-blast-radius changes unless explicitly enabled

## License

Apache License 2.0

