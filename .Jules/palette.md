## 2026-10-10 - Neumorphic Visual Design & Focus-Visible States
**Learning:** Neumorphic visual designs rely on `outline: none;` for standard elements to maintain soft shadow aesthetics, but without explicit `:focus-visible` styling, keyboard navigation indicators are completely lost.
**Action:** Always complement neumorphic `outline: none` CSS rules with explicit `:focus-visible` outlines using accent colors and `outline-offset` to maintain keyboard accessibility.
