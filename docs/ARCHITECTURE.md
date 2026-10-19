# Ideal / Blackwater architecture — public overview

```text
Game content and interaction rules
               |
               v
Canonical simulation / world state
       |                  |
       v                  v
Actor decisions      Spatial state
       |                  |
       +--------+---------+
                |
                v
      Read-only presentation
                |
                v
       Browser game client
```

The design separates authoritative simulation state from game-specific content and rendering. Asset workflows are validated and promoted before use. Reusable framework extraction into a separate repository is in progress; the working kernel remains associated with the combined development workspace.

This is a conceptual public diagram, not a claim that all planned systems are fully integrated.
