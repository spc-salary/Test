## 2025-05-18 - Focus-Visible States in Neumorphic Interfaces
**Learning:** Neumorphic design uses subtle box-shadows (`box-shadow: 6px 6px...`) that naturally eliminate standard browser focus outlines, leaving keyboard users without any visual focus indicator when navigating interactive elements.
**Action:** Always add explicit `:focus-visible` outline styles with contrasting accent colors (`outline: 2px solid var(--accent)`) to interactive elements in neumorphic UIs.
