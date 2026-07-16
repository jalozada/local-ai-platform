# ADR-002: Docker Compose Before Kubernetes

## Status

Accepted

## Context

The platform is beginning with local-first development and a limited set of services. Kubernetes would add operational complexity before the platform has established stable service boundaries and runtime requirements.

## Decision

The platform will use Docker Compose before Kubernetes. Compose will provide the initial service orchestration foundation while the platform architecture, runtime model, and operational needs mature.

## Consequences

This keeps the early platform understandable and locally operable. Kubernetes remains out of scope until there is a clear architectural and operational requirement for it.
