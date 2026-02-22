# AI SRE Root Cause Investigator

Correlate metrics, logs, and traces to infer probable root causes.

## Domain

infrastructure

## MVP Scope

1. Define data contracts and threat model.
2. Build core service/API skeleton.
3. Add observability and audit events.
4. Implement policy gates and baseline tests.
5. Ship a minimal demo workflow.

## Quick Start

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
pytest -q
python -m src.main
```
