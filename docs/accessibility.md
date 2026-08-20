# Accessibility

> Accessibility principles and implementation standards for the Ayur Clinic website.

## Overview

Accessibility is a core part of the Ayur Clinic website.

The platform is designed to provide a clear and usable experience for as many users as possible, regardless of device, input method, or accessibility requirements.

The project aims to follow WCAG 2.2 AA principles where applicable.

Accessibility is considered during design, development, and testing rather than being treated as a final-stage requirement.

---

## Core Principles

The website should be:

- Perceivable
- Operable
- Understandable
- Robust

Design and development decisions should support users who rely on:

- Keyboard navigation
- Screen readers
- Touch interfaces
- Zoomed or enlarged text
- Different screen sizes
- Reduced motion preferences

---

## Semantic HTML

Semantic HTML should be used wherever appropriate.

Examples include:

- `header`
- `nav`
- `main`
- `section`
- `article`
- `footer`
- `button`
- `form`
- `label`

Semantic elements provide meaningful structure and improve compatibility with assistive technologies.

Elements should not be selected purely for visual appearance.

---

## Keyboard Navigation

All interactive functionality should be accessible using a keyboard.

Users should be able to:

- Navigate interactive elements using the keyboard
- Clearly identify the currently focused element
- Activate controls without requiring a mouse
- Access navigation menus and interactive tools

Keyboard focus should follow a logical order through the page.

Keyboard users should never become trapped inside an interface component.

---

## Focus States

Interactive elements must provide visible focus states.

This includes:

- Buttons
- Links
- Form fields
- Navigation controls
- Calculator controls
- Other interactive elements

Focus indicators should remain visible and should not rely only on subtle colour changes.

---

## Colour and Contrast

Colour should not be the only method used to communicate meaning.

Important information should also be communicated through:

- Text
- Labels
- Icons where appropriate
- Structure
- Clear interaction states

Text and interface elements should maintain sufficient contrast against their backgrounds.

The visual design should balance the desired calm aesthetic with readable and accessible contrast levels.

---

## Typography

Typography should prioritise readability.

Key considerations include:

- Clear hierarchy
- Readable font sizes
- Comfortable line height
- Controlled line length
- Sufficient contrast
- Responsive scaling

Users should be able to zoom and enlarge content without losing important information or functionality.

Text should not depend on fixed layouts that break when font sizes increase.

---

## Headings and Content Structure

Headings should follow a logical hierarchy.

Pages should use headings to communicate the structure of the content rather than styling text to visually resemble headings.

A typical structure may include:

```text
H1 — Main page title
│
├── H2 — Major section
│   ├── H3 — Supporting section
│   └── H3 — Supporting section
│
└── H2 — Major section
