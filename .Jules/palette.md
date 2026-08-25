## 2025-05-15 - Neumorphic Focus States and Semantic Task Actions
**Learning:** Neumorphic visual designs natively remove standard border and background focus highlights, making focus-visible rings essential for keyboard accessibility. Additionally, dynamic task items built via raw innerHTML omit focusable action buttons and dynamic ARIA labels.
**Action:** Always add explicit `:focus-visible` outline rings on neumorphic controls and create dynamic list item buttons using `document.createElement` with descriptive `aria-label` attributes.
