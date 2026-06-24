---
name: obsidian-knowledge-graph
description: Organize notes, sources, study material, research, and personal knowledge into flexible Obsidian knowledge graphs. Use when the user asks to structure Obsidian notes, create or revise a vault/MOC, organize a project map, turn content into Topic/Resource/Concept notes, add bidirectional links, reduce folder overuse, avoid rigid templates, or maintain a reusable linked knowledge network.
---

# Obsidian Knowledge Graph

## Core Principle

Treat Obsidian as a knowledge manager, not a file manager.

Always follow:

```text
Folders organize files.
Links organize knowledge.
```

Use folders only for storage and broad grouping. Express knowledge relationships with `[[bidirectional links]]`.

## Note Types

Classify every new item as one of three note types before writing.

These structures are defaults, not mandatory templates. Adapt them to the material, the project stage, and the user's goal. Do not create empty sections or standalone notes just because a template contains them.

### Topic Notes

Use a Topic note as the entry point for a domain, course, research area, or long-term project. It is a navigation page, not a detail dump.

Use this structure:

```markdown
# Topic Name

## Core Concepts

- [[Concept A]]
- [[Concept B]]

## Important Resources

- [[Resource A]]
- [[Resource B]]

## Current Questions

## Next Directions
```

For active projects, use the Topic note as a project map. Include only useful entry points that exist or are immediately actionable, such as current goals, key resources, decisions, experiments, code entry points, or open questions.

### Resource Notes

Use a Resource note for a specific source: paper, book, video, website, course, lecture, report, interview, or official page.

Resource notes connect concepts. They should not become the center of the knowledge base.

Use this structure:

```markdown
# Resource Title

## Core Content

## Key Points

## Extracted Concepts

[[Concept A]]

[[Concept B]]

[[Concept C]]

## My Understanding
```

Create Resource notes only when there is a real source to record. Do not invent Resource notes for papers, datasets, pages, or code files that have not been provided or found.

### Concept Notes

Use a Concept note for reusable knowledge nodes: concepts, theories, methods, technologies, tools, models, people, organizations, events, universities, majors, exams, or application requirements.

Create a standalone concept note when the item:

- will appear again,
- is worth long-term accumulation,
- can connect to multiple notes.

Use this structure:

```markdown
# Concept Name

## Definition

## Core Content

## Key Features

## Use Cases

## Related Concepts

[[Concept A]]

[[Concept B]]

[[Concept C]]
```

Create Concept notes gradually. Do not pre-create a large concept taxonomy before there is enough content to justify it.

## Adaptive Project Rules

Do not use one fixed folder or note template for every project. First inspect the available material and infer the project's actual shape.

Use these defaults:

- Research projects: prioritize project maps, papers, research questions, experiment records, and concepts that recur across sources.
- Coding projects: prioritize architecture maps, key modules, setup/run notes, decisions, issues, and implementation records.
- Study projects: prioritize course maps, core concepts, problem types, resources, and review records.
- Application/planning projects: prioritize MOCs, requirements, deadlines, target lists, decisions, and action records.

Start small. Add new notes only when they solve a navigation, reuse, or evidence problem.

Avoid:

- creating many empty concept pages upfront,
- forcing every project into Topic/Resource/Concept folders immediately,
- treating folder names as knowledge relationships,
- converting speculative relationships into links,
- adding "complete-looking" structures that the source material does not support.

## Folder Rules

Do not use deep folder trees to express knowledge relationships.

Keep folders shallow, usually no more than two levels. Recommended vault-level layout:

```text
00_MOC
01_Concepts
02_Resources
03_Projects
99_Archive
```

For a domain folder, use:

```text
Domain
+-- 00_Home
+-- 01_Concepts
+-- 02_Resources
+-- 03_Records
```

Do not treat folder location as semantic truth. A note's relationships must be visible through links in the note body.

Folder layouts are optional scaffolding. If a project has only a few useful notes, keep the folder structure minimal.

## MOC Rules

Use MOC/navigation pages to organize access, not to store detailed knowledge.

Use this simple pattern:

```markdown
# Navigation Page

## Category A

- [[Note A]]
- [[Note B]]

## Category B

- [[Note C]]
- [[Note D]]
```

A MOC may link directly to important concepts, resources, and records if it improves navigation. This is expected and does not need to form a strict tree.

## Linking Rules

Link important entities explicitly:

```markdown
[[University]]
[[Major]]
[[Exam]]
[[Tool]]
[[Theory]]
[[Method]]
```

Prefer linked statements:

```markdown
[[University A]] offers or relates to [[Major B]].
```

Avoid unlinked knowledge-bearing entities:

```markdown
University A offers Major B.
```

If a relationship is uncertain, do not create a factual link statement. Write `To confirm` instead.

Avoid using `[[links]]` in examples or placeholder text when they would create misleading graph edges.

## Atomicity Rules

Keep one note focused on one subject.

Avoid combining:

```text
university profile + major explanation + application process + exam requirements
```

Split into reusable nodes:

```text
University A
University B
Major A
Major B
Exam A
Exam B
```

Connect them with links.

## Workflow

For each new piece of knowledge or project:

1. Inspect the actual material first: files, notes, sources, code, records, or user-provided text.
2. Decide whether the material needs a Topic, Resource, Concept, project map, record, or no new note.
3. Create or update only the notes that are currently useful.
4. Extract reusable concepts only when they will recur or connect multiple notes.
5. Add `[[bidirectional links]]` for confirmed relationships.
6. Add entry points from the relevant MOC or project map.
7. Keep uncertain facts as `To confirm` and avoid linking them as facts.

The goal is not to build a file tree. The goal is to build a reusable knowledge network.
