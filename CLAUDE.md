# Agent Hive - Agent Instructions

Multi-agent orchestration framework for FORGE portfolio.

## Tech Stack
- Python 3.13+
- Astral UV for dependencies
- asyncio for concurrency
- Redis for message queue (optional)

## Commands
```bash
uv sync           # Install dependencies
uv run pytest     # Run tests
uv run agent-hive # Start the hive
```

## Key Files
- `src/hive/controller.py` - Main orchestration logic
- `src/hive/agent.py` - Base agent class
- `src/hive/queue.py` - Message queue implementation
