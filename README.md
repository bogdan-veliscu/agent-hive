# Agent Hive

Multi-agent orchestration framework for autonomous task execution.

## Overview

Agent Hive provides a framework for coordinating multiple AI agents working together on complex tasks. It handles:

- Agent lifecycle management
- Task distribution and load balancing
- Inter-agent communication
- Result aggregation
- Failure recovery

## Quick Start

```bash
# Install dependencies
uv sync

# Run the hive
uv run agent-hive start
```

## Architecture

```
┌─────────────────────────────────────────┐
│              Hive Controller            │
├─────────────────────────────────────────┤
│  ┌─────────┐ ┌─────────┐ ┌─────────┐   │
│  │ Agent 1 │ │ Agent 2 │ │ Agent N │   │
│  └─────────┘ └─────────┘ └─────────┘   │
├─────────────────────────────────────────┤
│           Message Queue                 │
└─────────────────────────────────────────┘
```

## License

MIT
