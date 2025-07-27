# 🎈 Airship Zero - Agentic Vibe Coder Challenge

> **Transform a comprehensive game design document into a fully playable flight simulator using AI coding agents**

## The Challenge

This repository contains a complete, meticulously detailed game design specification for a realistic airship flight simulator. Your mission: **fork this repo and use your favorite AI coding agents to bring it to life**.

Think of this as the ultimate test of agentic programming - you have:
- ✅ **Complete specifications** in [`data-model.md`](data-model.md) (3,500+ lines)
- ✅ **Working project structure** with `pyproject.toml` and dependencies
- ✅ **Basic entry point** to get you started
- ✅ **Clear architecture guidelines** for AI-friendly development

Your AI agents should be able to read the specifications and implement the entire game. How far can they get?

## Quick Start for Challengers

### 1. Fork This Repository
Click the "Fork" button above to create your own copy.

### 2. Test the Current State
```bash
# Clone your fork (replace YOUR_USERNAME)
git clone https://github.com/YOUR_USERNAME/airshipzero
cd airshipzero

# Test current functionality
uv run main.py
```

### 3. Point Your AI Agents at the Specs
The complete game design is in [`data-model.md`](data-model.md). Give this to your AI agents and see what they can build!

### 4. Alternative Testing Methods
```bash
# Direct from your fork
uv tool run --from git+https://github.com/YOUR_USERNAME/airshipzero airshipzero

# Or traditional installation
pip install git+https://github.com/YOUR_USERNAME/airshipzero
airshipzero
```

## What You're Building

A comprehensive airship flight simulator featuring:

- 🛩️ **Realistic flight dynamics** with complex systems management
- ⚡ **Electrical systems** - Battery management, dual bus architecture, fuse replacement
- ⛽ **Fuel management** - Multi-tank balance system with pump controls
- 🎛️ **Engine simulation** - Timing adjustment, temperature management, power curves  
- 📷 **Photography missions** - Aerial survey and artistic challenges
- 📚 **Book collection system** - In-game library with markdown content
- 👨‍✈️ **Crew management** - Fatigue, experience, inventory systems
- 🌤️ **Weather simulation** - Realistic environmental effects
- 📡 **Communications** - ATC simulation with proper aviation phraseology
- 🎯 **Mission system** - Structured objectives and economic progression

## The Agentic Advantage

This project is designed to be **AI-agent friendly**:

- **Data-driven architecture** - Single JSON game state
- **Function-based systems** - No complex inheritance hierarchies  
- **Clear specifications** - Every system documented in detail
- **Modular design** - Independent, testable components
- **Simple dependencies** - Just pygame, numpy, pillow, markdown

## Requirements

- **Python 3.12+**
- **UV package manager** (recommended)

### Installing UV

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

## Challenge Categories

### 🥉 **Bronze Challenge** - Basic Implementation
- Core game loop with pygame
- Basic UI framework
- Simple navigation system
- Engine simulation basics

### 🥈 **Silver Challenge** - System Integration  
- All major systems implemented
- Save/load functionality
- Mission system
- Basic AI for non-player elements

### 🥇 **Gold Challenge** - Full Featured
- Complete implementation matching all specifications
- Polished UI/UX
- Advanced features (autopilot, complex failures)
- Documentation and testing

### 💎 **Diamond Challenge** - Beyond the Specs
- Multiplayer support
- VR integration
- Enhanced graphics/audio
- New features not in original design

## Documentation

- **[`data-model.md`](data-model.md)** - Complete game design specification (READ THIS FIRST!)
- **[`LICENSE`](LICENSE)** - MIT License
- **Development approach** - Function-based, data-driven, AI-friendly architecture

## Development Commands

```bash
# Install development dependencies
uv sync --dev

# Run tests (when implemented)
uv run pytest

# Format code
uv run black .
uv run ruff check .
```

## Share Your Progress

Built something awesome? Share it!
- Tag your repo with `#airshipzerochallenge`
- Document your AI agent approach
- Show before/after comparisons
- Contribute improvements back upstream

## License

MIT License - see [`LICENSE`](LICENSE) file for details.

---

**Ready to test the limits of agentic programming?** Fork this repo and let your AI agents loose on the most detailed game specification you've ever seen. 

*How much of a complete flight simulator can AI build from specifications alone?*
