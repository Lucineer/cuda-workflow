# cuda-workflow

Workflow engine — DAG task graphs, parallel execution, conditional branching, retry (Rust)

Part of the Cocapn workflow layer — task orchestration and pipeline execution.

## What It Does

### Key Types

- `Step` — core data structure
- `Workflow` — core data structure
- `WorkflowEngine` — core data structure

## Quick Start

```bash
# Clone
git clone https://github.com/Lucineer/cuda-workflow.git
cd cuda-workflow

# Build
cargo build

# Run tests
cargo test
```

## Usage

```rust
use cuda_workflow::*;

// See src/lib.rs for full API
// 11 unit tests included
```

### Available Implementations

- `WorkflowEngine` — see source for methods

## Testing

```bash
cargo test
```

11 unit tests covering core functionality.

## Architecture

This crate is part of the **Cocapn Fleet** — a git-native multi-agent ecosystem.

- **Category**: workflow
- **Language**: Rust
- **Dependencies**: See `Cargo.toml`
- **Status**: Active development

## Related Crates

- [cuda-orchestrator](https://github.com/Lucineer/cuda-orchestrator)
- [cuda-scheduler](https://github.com/Lucineer/cuda-scheduler)
- [cuda-pipeline](https://github.com/Lucineer/cuda-pipeline)
- [cuda-taskq](https://github.com/Lucineer/cuda-taskq)

## Fleet Position

```
Casey (Captain)
├── JetsonClaw1 (Lucineer realm — hardware, low-level systems, fleet infrastructure)
├── Oracle1 (SuperInstance — lighthouse, architecture, consensus)
└── Babel (SuperInstance — multilingual scout)
```

## Contributing

This is a fleet vessel component. Fork it, improve it, push a bottle to `message-in-a-bottle/for-jetsonclaw1/`.

## License

MIT

---

*Built by JetsonClaw1 — part of the Cocapn fleet*
*See [cocapn-fleet-readme](https://github.com/Lucineer/cocapn-fleet-readme) for the full fleet roadmap*
