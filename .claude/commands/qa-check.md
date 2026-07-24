---
description: Review the current state of index.html for issues that could embarrass us in front of investors, ranked by severity.
---

Review the current state of `index.html` (and any inline CSS/JS it contains) as it exists right now — do not assume anything from git history or prior conversations.

Check for:

- Placeholder text still lurking (`lorem ipsum`, `TODO`/`FIXME` comments, "click here" or similar filler copy)
- Missing `alt` text on images
- Broken or placeholder links (`href="#"`, `javascript:void(0)`, dead anchors)
- Unused CSS rules (selectors with no matching element in the markup)
- Accessibility basics (color contrast, semantic HTML — proper heading hierarchy, landmarks, labeled links/buttons)
- Anything else that would make Elena raise an eyebrow — vague copy, inconsistent spacing, unfinished-looking sections, anything that doesn't feel investor-ready

Deliver the findings as a succinct bullet list, ordered from most to least severe/important. For each bullet:

- State the issue plainly (what it is and where it is)
- Where possible, suggest or briefly describe a potential fix

Skip checks that pass — only report actual issues. If nothing of note is found, say so in one line rather than padding the list.
