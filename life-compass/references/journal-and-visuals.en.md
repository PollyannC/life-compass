# Local journal and visualizations

Default vault: `~/Desktop/Life coach/Journal/`; respect another location chosen by the user. Create needed directories on first actual use. Save or update an in-progress draft and diagram after each user contribution; verify and save again when the exploration or review ends or pauses. Resume the same draft when appropriate, and never overwrite a separate same-day session. If saving fails, report it, continue the conversation if possible, retry when feasible, and provide a copyable unsaved summary and diagram. Once access is restored, write only to the user's confirmed directory. Separate the user's own words from AI summaries, inferences, hypotheses, and advice; record only what was actually shared. Use non-sensitive titles and note date, source, status, and corrections. Modify or delete entries according to the user's wishes.

Chinese and English share one vault, stable filenames, and links. Switching languages must not rename, duplicate, or overwrite historical entries. Use the current language for new prose and diagram labels, while preserving the user's original words; add a clearly labeled translation only if requested. Even an English-first session uses the stable paths below, avoiding a second journal.

```text
Journal/
  首页.md                    # index: current direction, drafts, recent reviews
  方向/人生罗盘.md           # vision, anti-vision, values, identity, boundaries, versions
  日记/YYYY-MM-DD-主题.md    # each session; add a suffix on name collision
  主题/主题名.md             # recurring themes, sources, hypothesis status
  图形/YYYY-MM-DD-复盘.md    # Mermaid snapshot for every session
  图形/人生罗盘.canvas       # optional Obsidian JSON Canvas overview
```

Each entry captures the user's words and facts, feelings, actions actually taken, links to the vision, labeled inferences/hypotheses and uncertainties, progress and gaps, the user's chosen next step, next review question, and relevant `[[主题/主题名]]` links. Mark unfinished work in progress; do not record an unperformed action as completed. Preserve original context and corrections.

Show a concise Mermaid diagram or chart appropriate to the conversation and save its source in the session's `图形/` snapshot. Label nodes as user report, record, inference, hypothesis, imagined scenario, etc.; use dashed connections for hypotheses. Without data, draw a direction structure marked “not yet explored”; never invent progress. Explain that links show association, not proof of causation.

Obsidian Graph View derives relationships from note links; it is not a pre-generated static image and does not validate causality. Link theme indexes to source notes; label suggested cross-session associations “to confirm” until the user agrees. When free layout is useful, create or update valid JSON Canvas with `nodes` and `edges` arrays, file nodes pointing to existing Markdown notes, and stable unique IDs. Preserve manually arranged existing nodes and layout; if a safe merge is uncertain, keep the old file and create a candidate canvas instead.

Local notes are usually plaintext; privacy depends on device, backup, and existing sync settings. Do not promise encryption or exclusively local processing. Never upload personal journals, canvases, or summaries to GitHub, email, or another service without authorization. Exclude the whole Journal directory when sharing only the skill.
