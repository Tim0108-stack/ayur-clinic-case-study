# Architecture Decisions

> Key technical and product decisions made during the development of the Ayur Clinic website.

## Overview

This document records important architectural decisions made during the development of the Ayur Clinic website.

The purpose of documenting these decisions is to provide context for why certain technologies, structures, and approaches were chosen.

The project is currently under active development, and some decisions may evolve as requirements become clearer.

The central approach is:

> Build the initial platform simply, but build the foundation correctly.

---

## Next.js as the Application Framework

**Decision:** Use Next.js as the primary application framework.

The project requires a modern framework capable of supporting the current informational website while providing a foundation for future functionality.

Next.js provides:

- File-based routing
- App Router architecture
- Layout management
- Metadata support
- Server-side capabilities
- Strong React integration
- A scalable application structure

This allows the project to begin as a focused informational website without preventing future expansion.

---

## TypeScript for Application Development

**Decision:** Use TypeScript throughout the project.

The application contains structured content, reusable components, configuration, and future feature areas.

TypeScript helps provide consistency and improves confidence when modifying the application.

It is used to support:

- Component interfaces
- Structured data
- Shared types
- Configuration
- Feature development
- Refactoring

The objective is to improve maintainability as the project grows.

---

## Tailwind CSS for Styling

**Decision:** Use Tailwind CSS for styling and responsive development.

The website requires a consistent visual system across multiple pages and components.

Tailwind CSS supports:

- Responsive layouts
- Consistent spacing
- Typography systems
- Reusable styling patterns
- Efficient component development

The design system should remain consistent without requiring large amounts of disconnected page-specific CSS.

---

## Next.js App Router

**Decision:** Use the Next.js App Router architecture.

The App Router provides a structured approach to:

- Routes
- Layouts
- Page organisation
- Metadata
- Server and client functionality

Route groups are used where appropriate to organise sections of the application without affecting the public URL structure.

This supports a clear separation between areas such as the main marketing website and legal pages.

---

## Feature-Oriented Architecture

**Decision:** Separate feature-specific functionality from global shared components.

The application uses a structure that allows features to remain organised independently.

Examples include:

```text
features/
├── contact/
├── resources/
├── services/
└── team/
