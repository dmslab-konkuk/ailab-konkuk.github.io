---
layout: post
title: "G.A²Framework — Core Research (세부 1)"
---

# G.A²Framework: General-purpose Agent Architecture Framework

**Lead Researcher: 김청해 (Chunghae Kim)**

---

## Overview

The **G.A²Framework** aims to unify **Physical Agents (P.Agent)** and **Thinking Agents (T.Agent)** into a single, composable architecture — a universal agent framework powered by Dependency Injection (DI)-based modular design.

### Core Keywords
- DI-based Composable Architecture
- Long-Term Context-based Memory & Knowledge Framework
- Dynamic Proactive Multi-Agent Collaboration Model

---

## G.A²Framework Architecture

### Core + Plugins — Composable Agent Assembly at Runtime

The framework is built on **5 Core Modules** that can be extended with domain-specific plugins to generate diverse agent types at runtime:

| # | Core Module | Description |
|---|---|---|
| 1 | **Agent Core Engine** | Agent state management and execution lifecycle |
| 2 | **Perception** | External signal collection → standardized event transformation |
| 3 | **Cognition** | Situational judgment and plan formulation |
| 4 | **Action** | Command generation, execution, and feedback processing |
| 5 | **Learning & Memory** | Experience accumulation, GraphRAG, and federated learning |

---

## P.Agent vs T.Agent

The framework supports two fundamental agent paradigms through the same architecture:

| Phase | P.Agent (Physical) | T.Agent (Thinking) |
|---|---|---|
| **Perception** | Sensor / multi-modal signals | Text / API structuring |
| **Cognition** | Real-time safety planning | Dynamic workflow orchestration |
| **Action** | Motor / device control | Service / tool execution |
| **Learning** | Procedural memory | Semantic memory (Knowledge Graph) |

---

## Long-Term Memory & Knowledge Structure

### Recall Memory
- Separated into **short-term** and **long-term** stores
- Context storage and retrieval with temporal decay and relevance scoring

### Knowledge Graph
- **Tuple-based knowledge representation** for structured reasoning
- **GraphRAG inference** — combining graph traversal with retrieval-augmented generation for grounded, explainable answers

---

## Dynamic Proactive Multi-Agent Collaboration

### Blackboard Event-Driven Architecture

The multi-agent collaboration model is built on a **Blackboard pattern** with five shared spaces:

| Space | Role |
|---|---|
| **Context** | Shared situational awareness |
| **Event** | Trigger signals for agent activation |
| **Task** | Condition-based task creation and propagation |
| **Result** | Aggregated output from agent actions |
| **History** | Audit trail for reasoning and rollback |

### Concurrency & Recovery
- **Transaction integrity** across concurrent agent operations
- **Snapshot-based rollback** for fault tolerance and state recovery
