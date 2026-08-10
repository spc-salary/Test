# Palette's Journal

CRITICAL UX/accessibility learnings only.

## 2024-08-10 - Keyboard Nav and Focus Visuals in Flat/Neumorphic Design
**Learning:** Neumorphic design systems often rely heavily on shadows and inset states for interaction feedback while disabling standard element outlines. This can render the application completely unusable for keyboard-only or screen reader users if `:focus-visible` focus indicators are not explicitly styled, and if controls (like deletion spans) are implemented with generic non-semantic elements.
**Action:** When working on flat, minimal, or neumorphic design elements, always ensure custom `:focus-visible` rings are defined with a prominent accent color, replace plain `<span>` click handlers with semantic `<button>` elements, and use explicit `aria-label` labels for any icon-only controls.
