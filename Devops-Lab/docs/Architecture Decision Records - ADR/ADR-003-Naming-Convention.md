# ADR-003

## Title
Standardize virtual machine naming.

## Status
Accepted

## Context

The lab will grow over time and may include multiple operating systems.

## Decision

Prefix VM names with the operating system version.

Examples:

- rhel10-template
- rhel10-jenkins
- rhel10-k8s-master
- rhel10-k8s-worker
- rhel10-sonar

## Benefits

- Easy identification
- Easier migration
- Supports future labs
- Consistent naming

## Status

Accepted
