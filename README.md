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

The LLM is not treated as the authoritative source for numerical calculations.

Deterministic components independently calculate and validate critical results.

Experimental Conditions

The research compares three experimental conditions.

Experiment A — LLM Only
Human
  |
  v
LLM
  |
  v
Answer

This establishes the baseline performance of the language model without an independent computational architecture.

Experiment B — General-Purpose LLM + AL-Brain
Human
  |
  v
LLM
  |
  v
Structured Task
  |
  v
AL-Brain
  |
  +--> Calculation
  |
  +--> Validation
  |
  v
Answer

This evaluates whether deterministic computation and validation improve reliability.

Experiment C — Fine-Tuned LLM + AL-Brain
Human
  |
  v
Fine-Tuned LLM
  |
  v
Structured Task
  |
  v
AL-Brain
  |
  +--> Calculation
  |
  +--> Validation
  |
  v
Answer

This evaluates whether domain-specific adaptation provides additional improvements beyond the general-purpose LLM + AL-Brain architecture.

Evaluation

The benchmark will include static, dynamic, adversarial, and high-complexity industrial scenarios.

Scenarios may contain:

Multi-level bills of materials
Multiple production operations
Machine capacity constraints
Inventory limitations
Work-in-progress
Production batches
Deadlines and priorities
Setup times
Equipment downtime
Equipment failures
Material shortages
Quality defects
Changing conditions
Incomplete information
Conflicting information
Infeasible requirements
Ambiguous terminology

Evaluation metrics include:

Interpretation accuracy
Structured-task accuracy
Calculation accuracy
Constraint handling
Temporal reasoning
Contradiction detection
Incomplete-information detection
Hallucination rate
Clarification quality
Error recovery
Consistency
Generalization
Latency
Token usage
API cost
Research Principle

The goal is not to demonstrate that an LLM can replace specialized industrial software.

The goal is to determine:

Which reasoning and interpretation tasks can be reliably delegated to an LLM.
Which tasks require deterministic computational control.
Which errors can be detected by independent validation.
Whether domain-specific fine-tuning improves reliability and generalization.
Whether combining LLM reasoning with deterministic systems provides measurable advantages over LLM-only reasoning.
Status

Research prototype.

The project is under active experimental development.

License

MIT License
