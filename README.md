# AL-Brain

## Experimental Architecture for Reliable Industrial AI

AL-Brain is an experimental modular AI architecture for studying how large language models can be combined with deterministic computational and validation systems for complex industrial decision-making.

The project focuses on the boundary between natural-language reasoning and deterministic computation.

## Research Objective

The primary research question is:

> Can large language models reliably translate complex, dynamic industrial problems expressed in natural language into structured computational tasks, while an independent deterministic architecture validates the interpretation, calculations, constraints, and resulting decisions?

The research investigates both the capabilities and limitations of LLM-based reasoning in complex industrial environments.

## Research Domains

AL-Brain is designed to investigate AI-assisted decision making across:

- Production planning
- Manufacturing
- Inventory management
- Work-in-progress management
- Quality management
- Maintenance
- Logistics
- Resource management
- Capacity planning
- Constraint management
- Temporal planning

## Architecture

The experimental architecture separates language reasoning from authoritative computation and validation.

```text
Human
  |
  v
Large Language Model
  |
  v
Structured Task
  |
  v
AL-Brain
  |
  +--> Calculation
  |
  +--> Planning
  |
  +--> Constraint Validation
  |
  +--> Result Validation
  |
  v
Verified Result
  |
  v
Human
