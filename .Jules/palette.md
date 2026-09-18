## 2026-09-18 - Visible Focus States in Neumorphic Interfaces
**Learning:** Neumorphic design reliance on standard CSS `outline: none` removes browser default focus indicators, making keyboard navigation completely invisible to screen reader and keyboard-only users.
**Action:** Always add explicit `:focus-visible` ring/outline rules matching `--accent` colors for all interactive elements (buttons, inputs, dynamic controls) when working with soft/neumorphic UI components.
