## 2026-08-31 - Neumorphic Visual Design & Focus Visibility
**Learning:** Neumorphic CSS design (`outline: none`, inset/outset box shadows) natively hides browser default focus indicators, rendering interactive controls completely invisible to keyboard navigation.
**Action:** Always add explicit `:focus-visible` ring styling using design tokens (e.g., `var(--accent)`) for all interactive elements in neumorphic themes.
