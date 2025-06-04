# mtu-system-design

Please see the [Scheduling System](./scheduling-system.pdf)

## Introduction to My Approach: ADRs and C4 Model

My approach to this design challenge is to follow an [ADR like process](https://www.cognitect.com/blog/2011/11/15/documenting-architecture-decisions) and to use the [C4 Model](https://c4model.com/) for most things.

ADRs are usually used when a decision must be made and are generally framed around the presentation of options that might be chosen, nominating one. ADRs can, however, also document a single option. We'll see what I end up with.

For C4, I generally only use [context](https://c4model.com/diagrams/system-context) and [container](https://c4model.com/diagrams/container) diagrams, though I have used [component](https://c4model.com/diagrams/component) diagrams previously. I will otherwise use sequence or [dynamic](https://c4model.com/diagrams/dynamic) diagrams as needed. C4 diagrams are written in PlantUML (.puml extension) and rendered via it. Mermaid will also let you render C4 diagrams now but the diagram quality is still lower (criss crossing lines, etc.)

All diagrams will be in the `/diagrams` folder. The top level [System Design](./design.md) document will hold the entire solution.

