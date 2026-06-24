---
name: obsidian-knowledge-graph
description: Organize notes, sources, study material, research, and personal knowledge into an Obsidian knowledge graph. Use when the user asks to structure Obsidian notes, create or revise a vault/MOC, turn content into Topic/Resource/Concept notes, add bidirectional links, reduce folder overuse, or maintain a reusable linked knowledge network.
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

For each new piece of knowledge:

1. Decide whether it is a Topic, Resource, or Concept.
2. Create or update the corresponding note.
3. Extract reusable concepts.
4. Add `[[bidirectional links]]`.
5. Add entry points from the relevant MOC.
6. Keep uncertain facts as `To confirm`.

The goal is not to build a file tree. The goal is to build a reusable knowledge network.
