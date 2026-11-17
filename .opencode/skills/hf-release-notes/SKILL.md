---
name: hf-release-notes
description: Generate release notes from cached PR JSON files.
---

# Release Notes

1. Read every `.release-notes/tmp/pr_*.json` file.
2. Use each PR title, body, author, and labels to draft release notes.
3. Write `.release-notes/RELEASE_NOTES_v0.0.1.md`.
4. Include each PR exactly once and ensure the output is non-empty.
