# Calibrant

[![CI](https://github.com/nikhilteja30/calibrant/actions/workflows/ci.yml/badge.svg)](https://github.com/nikhilteja30/calibrant/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.11+](https://img.shields.io/badge/python-3.11%2B-blue.svg)](https://www.python.org/)

An eval-first harness for building trustworthy LLM agents.

**Status:** alpha — Milestone 0 scaffolding

---

## About

Calibrant is an open-source, domain-agnostic harness for building LLM agents
where every component declares a golden test dataset and acceptance bar *before*
implementation. The harness gates on eval suites, not vibes.

This is part of the Calibrant project — see also
[calibrant-verify](https://github.com/nikhilteja30/calibrant-verify), a
scientific claim-verification platform built on this library.

## Installation

```bash
pip install calibrant
```

Or with uv:

```bash
uv add calibrant
```

## Development Setup

```bash
git clone https://github.com/nikhilteja30/calibrant.git
cd calibrant
uv sync --all-extras --dev
uv run pytest
```

## License

MIT — see [LICENSE](LICENSE).
