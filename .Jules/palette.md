# Palette's Journal - UX & Accessibility Learnings

## 2026-10-11 - Neumorphic Design Keyboard Focus & Dynamic Task Action Accessibility
**Learning:** Neumorphic design relies on soft box shadows that obscure default browser outline indicators, hiding keyboard focus state. Additionally, dynamic item lists created with innerHTML and raw click handlers fail screen reader expectations and lack keyboard action accessibility.
**Action:** Always add explicit `:focus-visible` styles with distinct outline/ring colors in neumorphic apps, and build dynamic list items using `document.createElement` with focusable `<button>` elements and dynamic `aria-label`s.
