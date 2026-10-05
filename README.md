# interactor-aria-planner

A hierarchical task planner in Elixir with temporal scheduling, where a persona is defined by its capability set alone.

## What it is for

It plans and executes tasks for personas, players and agents alike, against domains such as the blocks world, and schedules them on a simple temporal network. `AGENTS.md` describes the architecture.

## Build and test

```sh
mix deps.get
mix test
```

The tests need a PostgreSQL server; `mise.toml` holds the connection settings.

## Licence

MIT; see `LICENSE.md`.
