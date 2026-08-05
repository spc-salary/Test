# Palette Journal - POMODORO APP

## 2026-08-05 - Semantic Deletion Buttons and Tab Progress Micro-UX
**Learning:** Non-semantic elements like custom `<span>` elements used as interactive close buttons are completely invisible to screen readers and keyboard users. Converting these to semantic `<button>` elements with clear `:focus-visible` ring styling and descriptive, dynamic `aria-label` attributes ensures high accessibility. Additionally, updating `document.title` to show the ticking timer is a highly appreciated, unobtrusive micro-UX that allows users to monitor focus times across background tabs.
**Action:** When working on lists with deletion/action items, always use semantic `<button>` elements with descriptive `aria-label`s instead of raw characters/spans. Always identify if background/tab awareness (like dynamic titles) can elevate the utility of a background application.
