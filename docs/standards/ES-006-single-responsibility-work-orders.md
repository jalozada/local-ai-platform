# ES-006: Single Responsibility Work Orders

## Status

Accepted

## Purpose

Keep project work focused, reviewable, and aligned with approved scope.

## Standard

Each work order should have a single primary responsibility. It should avoid mixing unrelated architecture, documentation, infrastructure, implementation, or tooling changes unless explicitly approved.

## Rationale

Focused work orders reduce review complexity, make acceptance criteria clearer, and preserve traceability between project intent and repository changes.

## Exceptions or Revisit Conditions

Closely related supporting changes may be included when they are necessary to complete the approved work. Revisit this standard if future project phases require larger coordinated changes with explicit planning.
