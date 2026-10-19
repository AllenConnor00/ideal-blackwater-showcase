# Ideal / Blackwater

**Experimental living-world simulation and RPG systems.**

Ideal explores simulation infrastructure for persistent, causally coherent worlds. Blackwater is a game prototype used to test whether those systems produce meaningful everyday interactions and player agency.

> **Source availability:** The working implementation is private. This repository is a public engineering overview, not a playable download.

## What has been prototyped?

The Blackwater VS0.2.6 fixture demonstrates bounded object and character interactions, including carrying, giving, placing, eating, purchasing, and work-related resource changes. It also includes small explorable locations and a browser-based client.

The VS0.2.7 living-neighborhood milestone includes partial spatial and navigation work, but a complete integrated, engaging neighborhood is **not** yet verified.

## Engineering questions

- How can world state remain authoritative across actors and presentation layers?
- How can interactions be reusable rather than hand-scripted for every object?
- How can a simulation support everyday activities without locking the player into one path?
- How should technical tests and human playtest feedback jointly guide iteration?

See [Architecture](docs/ARCHITECTURE.md) and [Evaluation approach](docs/ENGINEERING_DECISIONS.md).

## Current status and limitations

**Research/prototype stage.** The existing fixture has finite resources and does not persist a full game world between restarts. Historical playtesting identified significant gaps in freedom, variety, and engagement. Passing technical tests are not presented as proof of a finished game.

## Demonstrations

Only actual, cleared screenshots or footage will be added. None are included in this initial showcase.

## Source and attribution

The source code and development artifacts remain private. This showcase does not distribute the game or simulation kernel.
