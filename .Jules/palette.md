# Palette's Journal

## 2023-11-20 - Browser Tab Timer Visibility and Keyboard Navigability
**Learning:** In single-page applications like Pomodoro timers, users frequently switch tabs and lose visibility of their progress, causing anxiety. Providing browser tab title status updates completely resolves this. Furthermore, custom interactive list elements (such as `onclick` spans) fail basic keyboard and screen reader checks unless styled and handled as semantic `<button>` elements with clear focus indicators.
**Action:** Always include live status in `document.title` for tracking tools. Replace non-semantic interactive spans with `<button>` elements configured with custom, keyboard-accessible styles and custom ARIA labels.
