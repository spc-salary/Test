## 2025-10-19 - Neumorphic Visual Focus States & Accessible Dynamic Controls
**Learning:** Neumorphic CSS design soft-shadows hide default browser focus outlines, leaving keyboard users with no visual feedback when navigating interactively. Additionally, inline `onclick` string templates in dynamic tasks compromise accessibility and security.
**Action:** Always add explicit `:focus-visible` outline styles in neumorphic UIs and dynamically construct list elements using `document.createElement` with semantic, focusable `<button>` controls and descriptive `aria-label` attributes.
