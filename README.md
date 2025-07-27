# Airship Zero

A realistic airship flight simulator with complex systems management.

## Quick Start

Install and run directly using UV:

```bash
uv run --from git+https://github.com/timelessp/airshipzero main.py
```

Or clone and run locally:

```bash
git clone https://github.com/timelessp/airshipzero
cd airshipzero
uv run main.py
```

## Features

- Realistic airship flight dynamics
- Complex engine and electrical systems
- Fuel management mini-game
- Photography missions
- Book collection system
- Crew management and fatigue simulation
- Weather and environmental effects

## Requirements

- Python 3.10+
- UV package manager (recommended)

## Documentation

See [data-model.md](data-model.md) for complete game design and system specifications.

## Development

```bash
# Install development dependencies
uv sync --dev

# Run tests
uv run pytest

# Format code
uv run black .
uv run ruff check .
```

## License

MIT License - see LICENSE file for details.
