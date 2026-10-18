## 2026-10-18 - Neumorphic Design & Keyboard Accessibility Focus Rings
**Learning:** Neumorphic design systems often suppress browser default outlines (`outline: none`) to maintain soft convex/concave shadows, making keyboard navigation completely invisible to users relying on Tab/Shift+Tab.
**Action:** Always inspect custom UI button resets for missing outline styles and supply explicit `:focus-visible` ring/outline rules that match the accent color.
