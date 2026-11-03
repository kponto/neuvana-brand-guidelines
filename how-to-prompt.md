# How to prompt

These instructions are for humans.

You do not need to pick files. Point the agent at the repository and name the task. `readme.md` is the entry point. It tells the agent which files to open.

## Opening line

> Read readme.md first. Identify the task, open only the files it lists, and follow them. Do not invent anything those files do not contain.

For a guidelines document, one-pager, or deck, that is enough. `readme.md` routes the agent to `how-to-guidelines.md`, which lists its own required files.

## Review

- All customer-facing output goes to human review before publishing, and agent output lands in staging.
- Never paste customer-identifiable information or individual health data into an agent.
- Never paste Neuvana Health or Neuvalo material into the same agent project as this kit.
