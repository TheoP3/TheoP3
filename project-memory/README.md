# Project memory — GitHub Profile (public)

This folder retains reviewable project context, **not** automatic ChatGPT transcripts. Read the latest handoff, decisions, discussions and lessons before starting related work. Update dated entries alongside meaningful work. Link evidence (files, commits, PRs, issues); state when conclusions are tentative or reconstructed. Existing project documents take priority until reconciled.

Never commit passwords, secrets or unreviewed private conversations. The GitHub profile repository is public; only public-safe administrative notes belong here. For raw chats use separate private/encrypted storage after reviewing contents. GitHub does not automatically back up ChatGPT, and prior deleted chats are not restored by this setup.

## Index
- [Latest handoff](LATEST_HANDOFF.md)
- [Decision log](DECISION_LOG.md)
- [Discussion summaries](DISCUSSION_SUMMARIES.md)
- [Lessons learned](LESSONS_LEARNED.md)
- [Conversation archive index](CONVERSATION_ARCHIVE_INDEX.md)
- [Dated handoffs](handoffs/README.md)
- [Archive rules](conversation-archives/README.md)


## Images, screenshots and other visual assets
- Preserve project-relevant images, generated artwork, diagrams, visual references, UI screenshots, and their context when the files are available and we have permission to store them.
- Keep final, approved assets in the project's existing image/assets folder where possible. For discussion evidence use `project-memory/visual-archive/` (or another clearly linked folder). Use meaningful names and dates.
- Maintain a simple index with filename/path, date, source or creator, purpose, related conversation/decision, version, usage rights and whether the image is final or a draft.
- Prefer storing the original file plus any editable source when available; do not replace an original with a smaller or altered copy without noting the change. Record alt text or a brief description.
- Do not assume images embedded in ChatGPT messages are automatically exported, retrievable or backed up. Save the actual image files while available and verify they open; a Markdown link or description alone is not a backup.
- Do not upload personal photos, private screenshots, sensitive health information, credentials or copyrighted third-party images without a privacy and rights review. This is especially important in public repositories, and deleting a committed file may not erase it from Git history.
- Avoid large binary history in ordinary Git. For large image collections, use Git LFS or a separate protected archive and document the location. Never add secrets or raw, unreviewed chat exports.

## User-uploaded files and supporting materials
- Treat project-relevant uploads as potential source materials: PDF, Word, text/Markdown, spreadsheets, slide decks, ZIP archives, source code, audio/video, datasets, scans, images and other attached files.
- Preserve the **original uploaded file unchanged** when it is available, we have permission to retain it, and the location is suitable. Derived or converted copies should be separately named and linked to the original.
- For every retained upload, record in a dated index: filename, original format, date received (if known), provenance/owner, intended purpose, related project task/discussion, exact storage path or secure external reference, usage rights, privacy classification, and whether the original bytes were verified. Add a SHA-256 checksum when practical.
- Place safe, small project materials in a suitable existing documentation/assets folder, or `project-memory/upload-archive/`. Use private/encrypted external storage with an index reference for confidential files, personal information or large archives; never publish private documents just to simplify backup.
- Before storing an upload, inspect for passwords, API keys, private identifiers, personal records, unrelated conversations, third-party content and copyright/licensing restrictions. **Never commit unreviewed archives or exports.**
- Keep revision history; do not silently overwrite originals. Note when an uploaded file was superseded or removed for a documented reason.
- Do not assume that chat attachments are automatically included in ChatGPT exports, visible to future chats, or copied to GitHub. Preserve actual bytes while available and verify that the stored file opens; a summary, filename or link is not a complete backup.
- Never claim an upload has been backed up without confirming the destination and file. Do not reconstruct unseen or unavailable attachment contents from memory.
