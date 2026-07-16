# ES-001: Self-Documenting Files

## Purpose

This standard defines expectations for files that explain their role, ownership, and intended use through clear naming, structure, and concise documentation.

## Motivation

The platform is expected to grow over time. Self-documenting files reduce ambiguity, improve review quality, and make the repository easier to navigate without relying on undocumented context.

## Standard Header

When a file benefits from explicit context, include a concise header that explains:

- The purpose of the file.
- The system area or concern it belongs to.
- Any important usage constraints.

Headers should be short and technical. They should not repeat information that is already obvious from the filename or surrounding directory.

## Examples

Markdown documentation should begin with a clear title and a brief purpose statement.

```markdown
# Architecture

This document describes the architectural direction for the Local AI Platform.
```

Configuration files may include short comments for major sections.

```yaml
# Persistent platform service state.
volumes:
  service-data:
```

## Rationale

Self-documenting files support maintainability by making intent visible at the point of use. This improves onboarding, review, and future modification while avoiding excessive process documentation.
