# ZERO GRACE: TRINITY — Unreal Production Build

Foundation: Narrative Pro 2 + Ultra Game Template 1.3.

Recommended Fab: Turn-Based RPG Template for combat; Interactive Story Plugin only for presentation interactions that do not duplicate narrative state; environment bundles/maps for city/dungeon prototypes; HKH Attribute System only if selected as sole stat layer.

Canonical ownership: Narrative Pro owns Unreal quest/dialogue state; TRINITY domain owns calendar/time blocks, relationships, social stats, dungeon state, combat and cross-system Trinity progression.

Implementation: calendar/relationship state and battle rules are data-driven/versioned. Content authoring uses Narrative Pro/Blueprints; canonical rules in C++/testable modules where practical.

Gauntlet: calendar availability/dead-end analysis, relationship state transitions, battle legality, narrative save migrations, dungeon reset/persistence, controller/UI accessibility and performance.
