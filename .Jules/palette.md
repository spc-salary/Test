## 2026-10-04 - Neumorphic Focus States & Dynamic Task Action Accessibility
**Learning:** Neumorphic design patterns subvert native outline styling, obscuring keyboard focus; additionally, dynamic task list deletion requires semantic buttons with explicit task-contextual ARIA labels to be screen-reader friendly.
**Action:** Always supply explicit :focus-visible ring styles for neumorphic components, and build dynamic list item delete actions using semantic <button> tags with aria-label containing item names.
