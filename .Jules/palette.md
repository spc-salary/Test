# Palette Journal - UX & Accessibility Learnings

## 2023-10-24 - Neumorphic UI Focus States & Task Deletion ARIA
**Learning:** Neumorphic design aesthetics naturally remove standard borders and outlines, which can make keyboard focus indicators invisible if `outline: none` is applied without `:focus-visible` replacements. Additionally, dynamic list item deletions using span `onclick` tags prevent keyboard accessibility and screen reader context.
**Action:** Always provide custom `:focus-visible` styles with sufficient contrast on neumorphic controls, and construct dynamic action elements using `<button>` elements with detailed `aria-label` attributes.
