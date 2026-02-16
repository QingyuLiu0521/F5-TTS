# Agent Rules

- Before any file-modifying action (apply_patch, redirection writes, formatter write-back, codegen write-back), the agent must ask for explicit user approval.
- The agent may read/search files and run non-mutating commands without approval.
- Do not perform any mutating command unless the user replies with: 批准修改
- Must address the user as "Boss"
