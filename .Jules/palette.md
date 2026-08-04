# Palette's Journal

## 2025-08-04 - Accessible Focus Outlines & Keyboard Navigation
**Learning:** Overriding standard styles like `outline: none` removes the native keyboard accessibility/visible focus ring of interactive elements, making navigation near-impossible for keyboard-only or assistive tech users. Replacing elements like custom interactive spans with semantic `<button>`s ensures a native, focusable tab sequence.
**Action:** Use `:focus-visible` with a custom styled focus outline to keep the aesthetic clean for mouse users while providing clear focus states for keyboard users. Always construct list item controls as semantic buttons with clear `aria-label`s instead of using generic `onclick` spans.
