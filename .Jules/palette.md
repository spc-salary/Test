## 2026-09-16 - Dynamic Action Controls and Neumorphic Focus States
**Learning:** Neumorphic visual designs naturally remove default focus indicators, making keyboard navigation invisible. In dynamic task lists, using raw `innerHTML` with `span` click handlers creates inaccessible and un-focusable controls.
**Action:** Always add explicit `:focus-visible` outline styles for neumorphic components, build dynamic task nodes safely using DOM creation methods (`createElement`/`textContent`), and provide semantic, focusable `<button>` elements with descriptive dynamic `aria-label`s.
