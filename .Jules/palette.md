## 2025-05-18 - Keyboard Accessible Task Deletion and Neumorphic Focus States
**Learning:** Neumorphic design components natively hide focus outlines, and dynamically inserted task delete triggers using non-semantic HTML (`<span onclick="...">x</span>`) lock out keyboard and screen reader users.
**Action:** Use semantic `<button>` elements with dynamic `aria-label`s for task actions and add explicit `:focus-visible` ring/outline styles for all interactive elements.
