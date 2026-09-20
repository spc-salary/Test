## 2026-09-20 - Neumorphic Visual Focus & Accessible Task Management
**Learning:** Neumorphic visual designs natively obscure default focus states, making keyboard navigation invisible. Additionally, dynamically inserted list items with innerHTML introduce XSS risks and non-focusable deletion targets.
**Action:** Always add explicit focus-visible ring styles for interactive controls in soft-shadow UI themes, and construct dynamic items using safe DOM methods with semantic, focusable delete buttons containing descriptive aria-labels.
