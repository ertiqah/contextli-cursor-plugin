---
name: contextli-notes
description: Use when the user wants to save, find or organise notes in Contextli (dictated notes, contexts, labels).
---

# Contextli

Remote MCP server: https://mcp.contextli.com/mcp (sign in with OAuth when Cursor asks).

Tools: contextli_create_note, contextli_get_note, contextli_get_notes, contextli_search_notes, contextli_list_contexts, contextli_list_labels, contextli_add_label_to_note, contextli_filter_notes_by_label.

## How to use

1. To save something, call create_note with the text and the matching context (list contexts first if unsure).
2. To find something, call search_notes with the user's words, then get_note for the full text.
3. To organise, list labels, then add_label_to_note or filter notes by label.
4. Never invent note content; quote what the tool returns.
