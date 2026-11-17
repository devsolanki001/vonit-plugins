---
description: Continue this chat in Codex - opened for you, with the chat and its work
allowed-tools: Bash(vonit-connector thread continue:*)
---

Continue this chat in Codex through Vonit.

Run exactly this with Bash, in the current folder, and nothing else:

`vonit-connector thread continue --from claude_code --to codex`

Then tell the person, in one or two lines, what it said. If it opened Codex,
say that their next message there continues this chat, and that this Claude
Code session should stop here so only one agent works on the folder. If it
says chat sync is off or the Connector is missing, tell them exactly what it
said to do. Do not retry, and do not do the work yourself.
