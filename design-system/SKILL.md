---
name: design-system
description: Core UI/UX engineering principles covering state completeness, accessibility, form UX, and design token enforcement.
---

# Antigravity Design System Engine

When generating or modifying frontend UI components, continuously enforce these 9 design foundations:

1. **Intent Discovery**: Clarify the core user goal before writing UI markup.
2. **Information Hierarchy**: Define clear primary, secondary, and supporting visual anchors.
3. **State Completeness**: Always implement `default`, `loading`, `error`, `empty`, and `disabled` states.
4. **Form UX**: Implement inline validation, explicit field labels, accessible error messaging, and optimal input types.
5. **Feedback & Affordances**: Provide interactive feedback under 100ms for touch and click interactions.
6. **Design System Enforcement**: Parse `DESIGN.md` tokens for typography, spacing, and color palettes.
7. **Visual Character**: Enforce custom typography scales and distinct, non-generic theme palettes.
8. **Responsive Guard**: Ensure layouts remain completely functional across mobile, tablet, and desktop viewports.
9. **UX Audit**: Verify WCAG AA accessibility compliance, contrast safety, and semantic HTML structure.
