## 2023-10-27 - Neumorphic Design Keyboard Focus and Dynamic Task Accessibility
**Learning:** Neumorphic CSS design patterns subvert default outline states, making interactive elements invisible to keyboard navigators. Furthermore, dynamically added task items created with `innerHTML` lacking semantic delete buttons isolate screen reader users.
**Action:** Always complement neumorphic controls with explicit `:focus-visible` styling and ensure dynamic DOM item creation uses `document.createElement` with focusable `<button>` controls and descriptive `aria-label` attributes.
