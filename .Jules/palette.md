## 2025-09-30 - Neumorphic UI Keyboard Focus & Dynamic Task ARIA Labels
**Learning:** Neumorphic design elements lack standard borders and default focus rings, which creates invisible focus states for keyboard users. Furthermore, raw `innerHTML` task creation creates un-focusable deletion triggers and missing screen reader context.
**Action:** Always add explicit `:focus-visible` styles with custom outline colors, and build dynamic list items using `document.createElement` with semantic `<button type="button">` delete buttons and task-specific `aria-label` attributes.
