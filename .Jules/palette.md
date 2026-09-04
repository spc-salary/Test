## 2026-03-04 - Neumorphic Visual Focus and Dynamic Task Accessibility
**Learning:** Neumorphic design interfaces lack default focus borders and contrast, hiding keyboard focus state. Additionally, dynamically inserted list item controls built with raw `innerHTML` lack keyboard accessibility and create potential XSS risks.
**Action:** Always add explicit `:focus-visible` ring styles mapped to the primary accent token and build dynamic element controls using semantic, focusable `<button>` nodes with descriptive dynamic `aria-label`s.
