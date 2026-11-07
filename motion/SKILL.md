---
name: motion
description: Audit and generate deliberate UI micro-interactions, enter/exit transitions, and spring physics while respecting reduced motion settings.
---

# /motion Skill for Antigravity

Inspect or inject animation logic into the target component:

1. **Timing & Easing**: Use custom cubic beziers (e.g., `cubic-bezier(0.16, 1, 0.3, 1)`) rather than generic `ease-in-out`. Keep micro-interactions under 200ms.
2. **Enter/Exit States**: Apply explicit opacity and subtle spatial transforms (`translateY` or `scale`).
3. **Reduced Motion**: Wrap motion logic or CSS transitions in `@media (prefers-reduced-motion: reduce)` media queries.
4. **Performance**: Restrict animated properties exclusively to `transform` and `opacity` to prevent costly browser layout reflows.
