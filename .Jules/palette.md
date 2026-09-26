## 2025-05-18 - Neumorphic UI Focus States and Dynamic Timer Controls
**Learning:** Neumorphic design systems remove default borders/shadows on focus, hiding keyboard focus indicators entirely. Additionally, dynamic countdown displays and list task deletions require explicit ARIA roles/labels and semantic button elements rather than click-handler spans.
**Action:** Always add explicit `:focus-visible` ring/outline styles for interactive elements in neumorphic UIs and ensure dynamic list actions use semantic focusable `<button>` elements.
