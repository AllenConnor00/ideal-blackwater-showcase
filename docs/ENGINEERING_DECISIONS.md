# Evaluation and engineering decisions

## Technical correctness versus experience
Tests can verify state transitions, collision rules, navigation contracts, and reproducibility. They cannot establish whether a world is enjoyable or offers meaningful agency.

## Reusable interaction primitives
The design favors actions grounded in world state rather than bespoke scripting for every object combination. Breadth and depth remain open implementation challenges.

## Preserve negative evidence
Prior human playtests did not meet the intended experience standard. Their conclusions inform iteration rather than being rebranded as success.

## Separation of concerns
Ideal Framework is intended to own reusable simulation capabilities; Blackwater owns game-specific content and experience.
