---
name: unslop
description: Strip cliché AI aesthetic artifacts (purple glow, excessive rounded corners, low contrast) and replace with distinct brand styling.
---

# /unslop Skill for Antigravity

Inspect the designated UI component and purge all common AI boilerplate artifacts:

- **Purge Default Gradients**: Remove blue-to-purple background radial/linear overlays. Replace with clean solid surfaces or subtle single-color opacity steps.
- **Purge Glassmorphism Overuse**: Replace blurry semi-transparent dark backgrounds (`backdrop-blur-md bg-white/10`) with solid surfaces using crisp 1px borders.
- **Normalize Radii**: Enforce purposeful rounding (e.g., small `4px` or `6px` for controls, `8px` or `12px` for cards).
- **Elevate Typography**: Replace default tracking and generic font weights with clean optical scaling.
- **Fix Contrast**: Ensure all muted text passes WCAG AA minimum contrast standards (4.5:1 ratio).
