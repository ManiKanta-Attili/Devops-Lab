# ADR-002

## Title

Use a Golden Image for all virtual machines.

## Status

Accepted

## Context

The project requires multiple RHEL 10 virtual machines with a consistent baseline.

## Decision

Create a fully configured Golden Image and generate Full Clones for each server role.

## Benefits

- Consistent operating system configuration
- Faster provisioning
- Easier recovery
- Reduced configuration drift

## Alternatives

- Install every VM manually

## Decision Outcome

Accepted
