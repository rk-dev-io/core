# Framework
> This is a Public repository. But development is likely not to happen much.

## Overview
The goal is to keep the framework focused.

The core should remain lightweight and only contain functionality that belongs at the framework level. 

Prioritize clean architecture and long-term maintainability over quick solutions.

## Notes
- Keep the codebase modular.
- Avoid unnecessary dependencies between systems.
- Refactor when it improves the overall design.
- Dont let temporary solutions become permanent ones.

## Requirements
- `pnpm` to install dependencies and build the web interface.
- A running MongoDB instance. Configure its connection through the `core_database` convar; the default is `mongodb://127.0.0.1:27017/core`.

## Inspirations
Ideas and design choices are influenced by a number of games and projects, including:
- GTAWorld
- SA:MP
- ARC Raiders
- along with other games and frameworks. 
