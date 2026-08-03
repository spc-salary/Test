# Palette's Journal

## 2026-08-03 - Accessible Task Deletion and Outline Restoration
**Learning:** Standard single-page micro-apps often hide system outlines with `outline: none` for visual polish, ignoring keyboard navigation. Additionally, simple task implementations use static mouse-only elements (such as `<span>x</span>`) for deletions, which prevents screen readers and keyboard-only users from completing simple core flows.
**Action:** When designing minimalist interactions, always restore keyboard-focused elements using modern CSS selectors like `:focus-visible`, and replace raw inline text click targets with semantic `<button>` elements that carry localized or context-rich `aria-label` attributes.
