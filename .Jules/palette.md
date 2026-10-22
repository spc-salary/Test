## 2026-10-22 - Accessible Dynamic Task Items in Neumorphic UI
**Learning:** Neumorphic designs often remove standard focus outlines and use non-semantic elements (like `<span>` with `onclick`) for dynamic actions, making them invisible to keyboard focus and screen readers.
**Action:** Always provide explicit `:focus-visible` styling with sufficient contrast and build dynamic action elements using semantic `<button>` tags with descriptive `aria-label` attributes.
