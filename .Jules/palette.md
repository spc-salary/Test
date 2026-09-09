## 2026-03-31 - Focus visible and task button accessibility in neumorphic UI
**Learning:** Neumorphic visual designs hide default browser outlines and non-semantic task controls (`<span onclick="...">x</span>`) lack keyboard focus and screen reader labels.
**Action:** Always provide explicit `:focus-visible` outline styles for neumorphic components and use semantic, focusable `<button>` elements with descriptive dynamic `aria-label`s for task actions.
