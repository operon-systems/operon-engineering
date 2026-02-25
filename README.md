# Operon Engineering

Core engineering workspace governed by Operon policy and automation framework.

## Structure

- src/ — application source code
- tests/ — test suite
- docs/ — architecture and documentation

## Governance

This repository is subject to:

- Mandatory Pull Request workflow
- Required CI checks
- Organizational policy enforcement

Direct pushes to main are prohibited.

## Architecture

The engineering layer follows a minimal layered architecture:

- src/core/ — domain logic and policies
- src/api/ — interface and transport layer
- src/runtime/ — execution and orchestration layer

The architecture is designed for long-term evolvability, modular growth, and governance alignment.