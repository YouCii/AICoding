# AICoding Development Guidelines

Auto-generated from all feature plans. Last updated: 2025-11-14

## Project Overview

This project follows a specification-driven development workflow. All features are defined in specification files before implementation.

- **specs/**: This directory contains feature-specific documentation, including specifications, plans, and research. Each feature has its own subdirectory (e.g., `specs/001-feature-name/`).
- **.specify/**: This directory contains scripts and templates for the specification-driven workflow.
- **.coco/**: This directory contains commands for interacting with the development environment.

## Build & Commands

The following commands are available for development, testing, and deployment:

- **coco speckit.specify**: Creates a new feature specification.
- **coco speckit.plan**: Generates a plan for implementing a feature.
- **coco speckit.tasks**: Generates a task list for a feature.
- **coco speckit.implement**: Implements a feature based on the generated tasks.
- **coco speckit.analyze**: Analyzes the consistency of the specification, plan, and tasks.
- **coco speckit.clarify**: Clarifies any ambiguities in the feature specification.
- **coco speckit.checklist**: Generates a checklist for a feature.
- **coco speckit.constitution**: Creates or updates the project constitution.

## Code Style

- **[Language-specific, ONLY FOR LANGUAGES IN USE]**
- Follow the conventions defined in the `.specify/templates` directory.

## Testing

- **Test-First (NON-NEGOTIABLE)**: Tests are written before implementation.
- Tests are located in the `tests/` directory at the repository root.
- The project uses a variety of testing frameworks, including `pytest` and `cargo test`.

## Security

- Follow standard security best practices.

## Configuration

- Environment setup and configuration management are handled by the scripts in the `.specify/scripts/bash` directory.

## Recent Changes

- [LAST 3 FEATURES AND WHAT THEY ADDED]

<!-- MANUAL ADDITIONS START -->
<!-- MANUAL ADDITIONS END -->
