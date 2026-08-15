## 2026-08-15 - Neumorphic Visual Design & Focus-Visible States
**Learning:** Neumorphic visual designs rely on soft inner/outer box shadows which often suppress or obscure default focus outlines, rendering keyboard navigation invisible to users.
**Action:** Always complement neumorphic controls with explicit `:focus-visible` outline styles (such as `outline: 2px solid var(--accent); outline-offset: 2px;`) to ensure full accessibility without altering standard click/active visual effects.
