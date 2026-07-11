---
description: Run a lightweight quality-assurance pass on the static page and summarize issues with severity and remediation hints.
---

Review the current workspace and inspect the main deliverable, especially `index.html`, and any adjacent assets or inline styles/scripts that could affect the demo experience.

Perform a concise QA sweep for the following:

- Placeholder or unfinished text such as `lorem ipsum`, `TODO`, `FIXME`, `click here`, `coming soon`, or other obvious demo filler.
- Missing `alt` text on images, including decorative images that should be marked appropriately.
- Broken or placeholder links such as `href="#"`, `javascript:void(0)`, dead anchors, or links that point to non-existent pages.
- Unused or stale CSS rules that no longer affect the rendered page.
- Accessibility basics including color contrast, heading hierarchy, semantic HTML landmarks, link/button labeling, and keyboard-friendly interactions.
- Any other issue that would make Elena raise an eyebrow: vague copy, low-contrast text, inconsistent spacing, suspicious hidden content, or anything that feels unfinished for a live investor-facing demo.

Produce a short report in bullet form. For each bullet, include:

- A short description of the check.
- Any issues found.
- An indicative severity level chosen from `Critical`, `High`, `Medium`, or `Low`.
- A brief hint for resolution.

Structure the response like this:

- Overall status: `PASS`, `WARN`, or `FAIL`.
- Check summary bullets, one per check area.
- A short `Recommended next actions` section if anything needs attention.

If a check passes, state that clearly and keep the bullet brief. If a check fails, be specific about the issue and suggest the smallest practical fix.
