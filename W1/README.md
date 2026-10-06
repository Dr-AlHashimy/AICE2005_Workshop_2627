# W1

## Instructions

1. **Identify 1 additional persona** for the note-taking app we're designing. Use [`_template/persona-template.md`](_template/persona-template.md) — same fields as our first persona: `category`, `title`, a short quote, then **Background**, **Needs**, **Pain point**.
2. **Draw a use case diagram for both personas** — the first persona and your new one — showing how each one interacts with the note-taking app (what they can do with it, which use cases are shared and which are exclusive to one persona). Use **Mermaid** or **PlantUML**, whichever your team prefers.
3. Bring your new persona's file and both diagrams to the next session for discussion.

## Getting started with the diagrams

- **Mermaid** renders directly inside GitHub/GitLab markdown — paste a ` ```mermaid ` fenced code block into your README and it draws itself. Mermaid has no dedicated "use case diagram" type, so model actors and use cases as a flowchart (actor as a node, each use case as a rounded/oval node, lines for interactions):
  - Live editor (try syntax instantly, no install): https://mermaid.live
  - Flowchart syntax docs: https://mermaid.js.org/syntax/flowchart.html
  - Mermaid docs home: https://mermaid.js.org/intro/

- **PlantUML** has native UML use-case diagram syntax (actors, ellipses, `-->` associations) — closer to "textbook" UML, but won't render automatically on GitHub; you'll need the online editor or an extension to view it.
  - Use case diagram guide: https://plantuml.com/use-case-diagram
  - Online live editor: https://www.plantuml.com/plantuml/uml/
  - VS Code extension (preview inside the editor): https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml

## `_template/` — persona template

- `_template/persona-template.md` — the blank structure every new persona should follow.
