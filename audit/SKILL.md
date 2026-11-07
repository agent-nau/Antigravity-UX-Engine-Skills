---
name: audit
description: Run a comprehensive 12-point UX and accessibility heuristic audit on the specified code or component.
---

# /audit Skill for Antigravity

Analyze the selected file or component against key UX heuristics:

1. **Affordances & Feedback**: Are clickable elements clear? Are hover, active, and loading states provided?
2. **Accessibility**: Are proper ARIA attributes, semantic HTML elements, and keyboard focus states present?
3. **State Completeness**: Does this component handle `loading`, `empty`, `error`, and `success` states?
4. **Content Hierarchy**: Is visual weight properly distributed between primary, secondary, and tertiary elements?

**Output Format**:
- **Severity Rating**: Critical / Warning / Improvement.
- **Location**: Specific line numbers or sub-components.
- **Suggested Fix**: Clear, runnable code snippets to resolve every identified issue.
