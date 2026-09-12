# Retirement notice

`FlossWare/agent` is the predecessor to `FlossWare/loom-ai` and is no longer the canonical execution/orchestration architecture.

The architecture has moved to Loom:

- **Intent** describes the desired outcome.
- **Arbiter** interprets Intent and coordinates execution.
- **Worker** provides executable capability.
- **Model Gateway** provides provider-neutral model access.
- **Knowledge** preserves reusable understanding.
- **Evidence** and **Evaluation** establish what happened and whether the outcome was achieved.

The old `agent` / `agent-ai` implementation is retained here for historical reference and migration work. New execution/orchestration capabilities belong in `FlossWare/loom-ai`.

See the migration tracking issue in `FlossWare/agent` and the Loom architecture documentation for the current design.