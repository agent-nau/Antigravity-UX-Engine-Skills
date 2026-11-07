---
name: restyle
description: Eliminate generic AI visual tropes, apply DESIGN.md design tokens, and elevate component polishing.
---

# /restyle Skill for Antigravity

When executed on a component, file, or active selection:

1. **Token Verification**: Read `DESIGN.md` in the workspace root if present. If missing, establish baseline parameters:
   - Primary typography, explicit color scale (avoid pure `#000` or generic `#3b82f6`), consistent spacing scale, border-radius token.
2. **Visual Slop Removal**:
   - Strip uniform large border-radii (`rounded-2xl` on everything).
   - Strip ambient multi-color floating radial gradients.
   - Strip low-contrast gray-on-gray secondary text.
   - Ensure distinct hover/active/focus-visible states.
3. **Four-Axis Diagnosis**:
   - **Type**: Hierarchy, optical balance, font weight pairing.
   - **Color**: Surface layering, token consistency, WCAG AA contrast.
   - **Space**: Visual density, padding ratios, layout alignment.
   - **Finish**: Micro-borders, shadows, interactive affordances.
4. **Output**: Return optimized code alongside a concise "Before vs. After" structural breakdown.
