# Airship Zero

A realistic airship flight simulator with complex systems management.

## Quick Start

### Method 1: Clone and run locally

```bash
git clone https://github.com/timelessp/airshipzero
cd airshipzero
uv run main.py
```

### Method 2: Using UV tool command

```bash
uv tool run --from git+https://github.com/timelessp/airshipzero main.py
```

### Method 3: Traditional pip installation

```bash
pip install git+https://github.com/timelessp/airshipzero
airshipzero
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

### Installing UV

UV is a fast Python package manager. Install it using one of these methods:

**Linux/macOS:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows (PowerShell):**
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Alternative methods:**
```bash
# Using pip
pip install uv

# Using pipx
pipx install uv

# Using Homebrew (macOS)
brew install uv

# Using Scoop (Windows)
scoop install uv
```

For more installation options, see the [UV documentation](https://docs.astral.sh/uv/getting-started/installation/).

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
