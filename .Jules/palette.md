## 2026-09-06 - Neumorphic UI Keyboard Focus & Dynamic Task A11y

**Learning:** Neumorphic design systems natively remove default button/input outlines via `outline: none`, completely hiding focus indicators for keyboard users. Additionally, dynamic item insertion using `innerHTML` with `onclick` spans creates non-focusable controls lacking ARIA labels.

**Action:** Always provide explicit `focus-visible` ring outlines for interactive controls in neumorphic designs, and generate dynamic items using `document.createElement` with semantic, focusable `<button>` elements and descriptive `aria-label` attributes.
