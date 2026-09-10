## 2026-09-10 - Neumorphic Focus States and Dynamic Action Buttons
**Learning:** Neumorphic UI design relies on soft box-shadows and removes default outlines, which completely hides keyboard focus states. Additionally, dynamic lists often use non-focusable spans for item deletion.
**Action:** Explicitly define `:focus-visible` styles with a clear accent outline for interactive components, and ensure dynamic elements (like delete buttons) use focusable `<button>` tags with descriptive, dynamic `aria-label` attributes.
