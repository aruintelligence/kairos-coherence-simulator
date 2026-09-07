# Kairos Coherence Simulator

A reproducible Python simulator for exploring coherence dynamics, ethical guardrails, and contemplative reflection.

[![Python](https://img.shields.io/badge/Python-3.8+-2563eb?style=flat-square&logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)](LICENSE)
[![Repository stars](https://img.shields.io/github/stars/aruintelligence/kairos-coherence-simulator?style=flat-square)](https://github.com/aruintelligence/kairos-coherence-simulator/stargazers)

> **Scope:** This is a symbolic, contemplative research tool—not therapy, meditation instruction, spiritual authority, or a measurement of consciousness.

## Features

- Seeded, reproducible stochastic simulations
- Validated configuration and resettable state
- Coherence, distortion, and stability trajectories
- Guardian Veto™ guardrail behavior
- CLI modes for simulation, summaries, logs, and reflections
- Optional Plotly dashboard and HTML export
- Structured JSON output
- Tögal- and Trekchö-inspired prompts, clearly framed as poetic reflection

## Quick start

```bash
git clone https://github.com/aruintelligence/kairos-coherence-simulator.git
cd kairos-coherence-simulator
python kairos_echo.py --mode run --steps 500 --seed 42
python kairos_echo.py --mode summary
python kairos_echo.py --mode togal
```

Plotly is only required for dashboard mode:

```bash
python -m pip install plotly
python kairos_echo.py --mode dashboard --save-html dashboard.html
```

## Reproducibility

A fixed `--seed` reproduces a simulated trajectory. The resulting values describe internal simulator state; they are not clinical, psychological, scientific, or spiritual measurements.

## Related projects

- [Kairos Echo Reflection Tool](https://github.com/aruintelligence/kairos-echo-reflection-tool)
- [Kairos Echo Inward Mirror](https://github.com/aruintelligence/kairos-echo-inward-mirror)
- [ĀRU Intelligence public research](https://github.com/aruintelligence/aru-intelligence-ai)

## License

Released under the [MIT License](LICENSE). Dzogchen terms belong to living religious traditions and are used respectfully as inspiration, without claiming lineage or authority.
