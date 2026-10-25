## 2025-10-25 - Neumorphic Design Focus & Task Creation Accessibility
**Learning:** Neumorphic visual designs remove default outlines, hiding keyboard focus. Explicit `:focus-visible` ring styling using `var(--accent)` restores keyboard navigation without altering active neumorphic shadows.
**Action:** Always add `:focus-visible` rules for interactive elements in neumorphic UIs, and use semantic `<button>` tags with task-specific `aria-label` attributes for dynamic item actions.
