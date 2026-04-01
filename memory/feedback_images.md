---
name: Images in dedicated folder
description: Images should go in a dedicated folder (e.g. docs/img/) and document refs must match
type: feedback
---

Put images in a dedicated subfolder within docs/ (e.g. `docs/img/`) rather than in the docs/ root. Update all image references in documents to match (e.g. `![alt](img/filename.jpg)`).

**Why:** MkDocs convention; keeps assets organized and separate from content.

**How to apply:** Whenever setting up or migrating a MkDocs project, create `docs/img/` for images and reference them as `img/filename` in markdown.
