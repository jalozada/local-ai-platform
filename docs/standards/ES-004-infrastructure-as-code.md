# ES-004: Infrastructure as Code

## Status

Accepted

## Purpose

Define expectations for managing platform infrastructure through version-controlled files.

## Standard

Infrastructure and operational configuration should be represented as code whenever practical. Manual setup steps should be minimized, documented when unavoidable, and replaced with reviewed configuration as the platform matures.

## Rationale

Infrastructure as Code improves repeatability, reviewability, recovery, and operational confidence. It also keeps infrastructure changes visible in the same engineering process as application and platform changes.

## Exceptions or Revisit Conditions

Exceptions are allowed for temporary local experimentation or external systems that cannot be represented in repository-managed configuration. Revisit this standard when infrastructure requirements expand beyond the current repository scope.
