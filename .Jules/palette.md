## 2025-05-18 - Neumorphic Focus States and Dynamic Task Accessibility
**Learning:** Neumorphic visual designs natively remove standard focus rings using `outline: none`, making keyboard navigation invisible. Additionally, dynamically appended list items using `innerHTML` often introduce non-semantic clickable `<span>` elements and potential XSS vectors.
**Action:** Always provide explicit `:focus-visible` outline styles for all buttons and inputs in neumorphic UIs, and build dynamic elements using `document.createElement` with semantic `<button>` tags and dynamic `aria-label`s.
