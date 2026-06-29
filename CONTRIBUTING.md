# Contributing Guide

Thank you for your interest in contributing to Intelligent Test Architecture.

This project follows engineering practices focused on scalability, maintainability, governance and Quality Engineering.

## Contribution Principles

Every contribution must follow these principles:

- Clear purpose
- Architectural justification
- Low coupling
- High cohesion
- Reusability
- Maintainability
- Documentation when needed
- Tests when applicable

## Before Creating Code

Before adding a new component, answer:

1. What problem does this change solve?
2. Which layer is responsible for this behavior?
3. Does this change introduce coupling?
4. Does this change require an ADR?
5. How will this scale with multiple contributors?

## Commit Pattern

Use conventional commits:

```txt
feat: add centralized environment configuration
fix: correct environment fallback behavior
docs: add quality engineering strategy
chore: update project dependencies
refactor: improve config structure
test: add smoke login scenario

Architecture Rules
Tests must not contain selectors.
Pages must not contain business rules.
Flows must not contain assertions.
Assertions must not prepare test data.
Fixtures must not validate UI behavior.
Config must centralize environment concerns.
Direct access to process.env outside config is not allowed.
Pull Request Checklist

Before opening a pull request:

 The change has a clear purpose.
 The architecture impact was considered.
 Documentation was updated when needed.
 Tests were added or updated when applicable.
 No sensitive data was committed.
 No duplicated responsibility was introduced.
Quality Mindset

This project is not only about automated tests.

It is about transforming automation into a Quality Engineering platform capable of supporting technical and business decision-making.