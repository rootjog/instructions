# instructions
Instructions for agents


## Tree
- `python.instructions.md`: Python guidelines.

## Usage
Create a personal instruction file with Copilot chat, paste this into the instruction file:

```prompt
---
description: These instructions files provides coding guidelines such as triggers that should be used when generating code, features, reviewing changes, should be fired when asked to do so or usage is recommended.
applyTo: **/*
---

Read the [rootjog instructions](https://github.com/rootjog/instructions) and apply them, use always the fetch tool for that.

<tasks>
First read the README from the repo [https://github.com/rootjog/instructions](https://github.com/rootjog/instructions).
</tasks>
<tasks> Read the instructions in the instructions folder of the repo, and apply them when generating code, reviewing changes, or when asked to do so. You can find the instructions at [https://github.com/rootjog/instructions](https://github.com/rootjog/instructions).
</tasks>
```
