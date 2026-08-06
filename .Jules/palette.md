# Palette's Journal

A journal of critical UX and accessibility learnings.

## 2024-08-06 - Neumorphic Interface Accessibility
**Learning:** Neumorphic design elements heavily rely on soft drop-shadows and low-contrast borders which can make focus states invisible if `outline: none` is used. Standard outlines look disjointed on rounded neumorphic shapes, but custom `focus-visible` outline styles with appropriate `outline-offset` preserve the aesthetic while restoring accessibility.
**Action:** Always provide custom `:focus-visible` styles with a well-offset outline that uses the theme's accent color.
