# Contributing

> Development and contribution guidelines for the Ayur Clinic website.

## Overview

The Ayur Clinic website is currently under active development.

This document outlines the general approach for contributing to the project and maintaining consistency across the codebase.

The goal is to ensure that new work aligns with the existing architecture, design system, accessibility standards, privacy principles, and development practices.

---

## Project Principles

Contributions should follow the core principles of the project:

- Keep responsibilities clearly separated
- Prefer reusable components
- Maintain type safety
- Avoid unnecessary complexity
- Follow the established design system
- Consider accessibility during development
- Consider responsive behaviour
- Protect privacy and sensitive information
- Avoid unnecessary dependencies
- Keep code understandable and maintainable

The central principle is:

> Build the initial platform simply, but build the foundation correctly.

---

## Before Making Changes

Before starting work on a new feature or significant change:

1. Understand the purpose of the feature.
2. Review the existing architecture.
3. Check whether a reusable component or existing pattern already solves the problem.
4. Consider responsive behaviour.
5. Consider accessibility requirements.
6. Consider privacy and security implications if data is involved.

New functionality should fit into the existing structure rather than creating unnecessary parallel patterns.

---

## Project Structure

The application follows a modular structure:

```text
src/
├── app/
├── assets/
├── components/
├── config/
├── content/
├── features/
├── lib/
├── providers/
└── types/
