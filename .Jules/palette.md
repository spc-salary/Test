## 2026-10-15 - Neumorphic Focus States and Dynamic Action Labels
**Learning:** Neumorphic design interfaces rely heavily on soft background shadows and often omit default focus borders. Additionally, dynamically inserted task delete triggers using plain `<span>` tags hide actions from screen reader users and keyboard navigation.
**Action:** Always provide explicit `:focus-visible` styling with high contrast outline colors for neumorphic components, and construct dynamic action triggers as semantic `<button>` elements with descriptive dynamic `aria-label`s.
