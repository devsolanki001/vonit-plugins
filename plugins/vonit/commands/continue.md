---
description: Continue this chat in Codex (or /vonit:continue gemini, opencode, goose, aider) - opened for you, with the chat and its work, even at a usage limit
allowed-tools: Bash(vonit-connector thread continue:*)
---

Continue this chat in Codex through Vonit.

Normally Vonit's prompt hook does this before you are asked, with no model.
You are reading this only if that hook is not installed.

Run exactly this with Bash, in the current folder, and nothing else:

`vonit-connector thread continue --from claude_code --to codex`

If the person asked to bring this project's setup too (its MCP servers, skills,
commands), add `--bring-setup`.

Then tell the person, in one or two lines, what it said. If it opened Codex,
say that their next message there continues this chat, and that this Claude
Code session should stop here so only one agent works on the folder. If it
says chat sync is off or the Connector is missing, tell them exactly what it
said to do. Do not retry, and do not do the work yourself.
