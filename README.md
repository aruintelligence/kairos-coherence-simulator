Harden Kairos Echo into a reproducible CLI coherence simulator with validated config, resettable state, dashboard export, and stable JSON logging

This commit upgrades Kairos Echo from a poetic prototype into a clean, release-ready single-file simulator focused on reproducibility, safety, and usability.

Key improvements:
• Added SimulationConfig dataclass with full defensive validation
• Added RunSummary dataclass for structured reporting
• Split action typing (InputActionType vs RecordedActionType)
• Hardened step() with explicit input validation
• Implemented deterministic reset() with RNG reseeding for true repeatable reruns
• Added run(reset=True) for predictable execution
• Added guards against empty history for summary, plotting, and export
• Made Plotly import lazy (non-dashboard modes no longer require it)
• Added optional HTML dashboard export via --save-html
• Fixed JSON serialization to preserve boolean values correctly
• Improved CLI flow and output for all modes (run, summary, dashboard, togal, trekcho, log)
• Preserved contemplative Tögal and Trekchö reflections while clearly framing the tool as symbolic

# Kairos Echo — Python Coherence Simulator with Tögal & Trekchö Reflections

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Stars](https://img.shields.io/github/stars/YOURUSERNAME/kairos-echo?style=social)](https://github.com/YOURUSERNAME/kairos-echo/stargazers)

**Lightweight Python coherence simulator** blending stochastic dynamics, ethical "guardian veto" guardrails, and gentle **Dzogchen-inspired** contemplative reflections (Tögal & Trekchö).

A poetic tool for **mindfulness**, inner awareness, and personal reflection. Features reproducible simulations, rich CLI modes, interactive Plotly dashboard, and clean JSON logging.

> **Disclaimer**: This is a **poetic / contemplative reflection tool** — not literal meditation software, enlightenment training, or spiritual simulator. Use it lightly for self-observation.

### ✨ Key Features
- Fully reproducible stochastic coherence dynamics with isolated RNG & seed control
- Ethical **guardian veto** — safely limits outward actions when coherence is low
- Tögal stage proxy (0–4) mapped to the Four Visions with evocative reflections
- Classic Trekchö reminders ("Short moments, many times")
- Multiple CLI modes: `run`, `summary`, `dashboard`, `togal`, `trekcho`, `log`
- Interactive **Plotly dashboard** with optional HTML export
- Defensive validation, resettable state, and stable JSON symbiosis logs
- Single-file design — minimal dependencies

### 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/YOURUSERNAME/kairos-echo.git
cd kairos-echo

# Install dependencies
pip install -r requirements.txt

# Run a simulation
python kairos_echo.py --mode run --steps 500 --seed 42

# Tögal reflection only
python kairos_echo.py --mode togal

# Interactive dashboard
python kairos_echo.py --mode dashboard --save-html dashboard.html

# Full summary with stats
python kairos_echo.py --mode summary
