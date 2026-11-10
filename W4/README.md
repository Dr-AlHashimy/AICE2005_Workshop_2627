# W4

## Instructions

1. **Open the UML cheatsheet** — [`_resources/uml-cheatsheet.pdf`](_resources/uml-cheatsheet.pdf). It shows the standard notation for class, sequence, package, object and use case diagrams, plus worked sample class diagrams (Library, Invoice, Component).
2. **Create a design diagram for your app** — take the class diagram you drafted in W3 and turn it into a *design-level* diagram, using the notation from the cheatsheet. Your diagram should show:
   - **Visibility** on every attribute and operation: `+` public, `-` private, `#` protected.
   - **Types** for attributes, parameters and return values, e.g. `-title : String`, `+addTag(tag : Tag) : void`.
   - **Multiplicity** on every association end, e.g. `1`, `*`, `0..1`.
   - **The right relationship for each link** — association, aggregation, composition, generalisation (inheritance), dependency, or realisation (class implements an `<<interface>>`).
   - **Packages** grouping related classes, e.g. `UI`, `Model`, `Storage` — with dependency arrows between packages.
3. **Check it against your requirements** — every functional requirement from W2 should be supported by at least one class or operation in the diagram. Note any requirement that isn't covered, and any class that doesn't serve a requirement.
4. Bring your design diagram to the next session for discussion.

## Getting started with the diagram

- **Mermaid** renders directly inside GitHub/GitLab markdown — paste a ` ```mermaid ` fenced code block into your README and it draws itself. Mermaid supports visibility, types, multiplicity, `<<interface>>` and all relationship arrows; use `namespace` blocks for packages.
  - Class diagram syntax: https://mermaid.js.org/syntax/classDiagram.html
  - Live editor (try syntax instantly, no install): https://mermaid.live

- **PlantUML** has native UML package and class syntax — closer to the cheatsheet notation, but won't render automatically on GitHub; you'll need the online editor or an extension to view it.
  - Class diagram guide: https://plantuml.com/class-diagram
  - Package diagram guide: https://plantuml.com/package-diagram
  - Online live editor: https://www.plantuml.com/plantuml/uml/
  - VS Code extension (preview inside the editor): https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml

## `_resources/` — reference material

- `_resources/uml-cheatsheet.pdf` — UML notation cheatsheet. (cc) 2006 Lou Franco, [CC BY-NC-SA 2.5](http://creativecommons.org/licenses/by-nc-sa/2.5/).
