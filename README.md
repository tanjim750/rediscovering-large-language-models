# Rediscovering Large Language Models

> **Don't just learn Large Language Models—rediscover them.**

This project is a first-principles journey to understand Large Language Models (LLMs), not by memorizing architectures, APIs, or frameworks, but by rediscovering the ideas that led to their creation.

The goal is to answer questions like:

* Why do Large Language Models work?
* Why were Transformers invented?
* Why does Attention exist?
* Why are embeddings necessary?
* Why did previous approaches fail?
* If we had to build everything from scratch today, how would we do it?

Instead of treating LLMs as a black box, this project breaks every concept down into its underlying problems, engineering decisions, mathematical intuition, and implementation.

---

# Vision

The vision of this project is simple:

> **Understand intelligence by understanding how we built it.**

Most learning resources teach *what* to use.

This project focuses on:

* Why it exists.
* How it works.
* Why previous solutions were insufficient.
* What trade-offs were made.
* How to rebuild it from first principles.

The objective is not only to understand today's LLMs, but also to develop the intuition required to reason about future architectures.

---

# Purpose

Modern AI education often focuses on using models.

This project focuses on understanding them.

By the end of this journey, the goal is not simply to know terms like *Transformer*, *Attention*, or *RAG*, but to understand:

* why each component exists,
* what problem it solves,
* where its limitations are,
* and how to improve or redesign it.

The ultimate goal is to think like an AI engineer and researcher rather than simply an AI user.

---

# Learning Philosophy

![Learning Philosophy](learning_philosophy.png)

Every topic in this project follows the same learning philosophy.

```text
Question
    ↓
Problem
    ↓
Hypothesis
    ↓
Theory
    ↓
Implementation
    ↓
Experiment
    ↓
Reflection
```

## Question

Learning starts with curiosity.

Ask what you want to understand before searching for the answer.

## Problem

Understand why the concept exists.

Every engineering solution was created to solve a problem.

## Hypothesis

Before reading the official explanation, create your own.

Your hypothesis does not need to be correct.

The goal is to train independent thinking.

## Theory

Learn the established explanation.

Compare it with your own hypothesis.

Understand not only *how*, but also *why*.

## Implementation

Knowledge becomes understanding only after building.

Every important concept should eventually be implemented from scratch.

## Experiment

Break things.

Change parameters.

Remove components.

Observe failures.

Many intuitions come from understanding why something stops working.

## Reflection

Every chapter ends with reflection.

Ask yourself:

* What did I actually learn?
* What assumptions were wrong?
* What limitations remain?
* If I redesigned this today, what would I try differently?

---

# What Makes This Project Different?

This is **not**:

* another prompt engineering course,
* another "use this API" tutorial,
* another framework guide,
* another collection of definitions.

Instead, this project is built around five principles:

## 1. First Principles

Every concept starts from the problem it solves.

Instead of introducing Attention immediately, we first ask:

> Why wasn't RNN enough?

---

## 2. Intuition Before Mathematics

Mathematics explains intuition.

It should never replace it.

Every mathematical concept is introduced only after the reader understands *why* it is needed.

---

## 3. Build Everything

Reading is not enough.

Every major component is implemented from scratch.

Examples include:

* Tokenizer
* Embeddings
* Self-Attention
* Transformer Block
* Tiny GPT
* RAG
* AI Agent

---

## 4. Learn Through Experiments

Understanding comes from observation.

Instead of simply accepting the current solution, we ask:

* What happens if this component is removed?
* What happens if we change it?
* Why does it fail?

---

## 5. Research Mindset

Knowledge should not end with implementation.

Every topic should inspire new questions.

The objective is to develop original intuition while remaining grounded in evidence and current research.

---

# Roadmap

![Roadmap](roadmap.png)

The complete journey consists of the following phases:

1. Computer Fundamentals
2. Mathematical Language
3. Information & Learning
4. Neural Networks
5. Language Representation
6. Sequence Modeling
7. Attention
8. Transformer
9. Training
10. Inference
11. Modern LLM Systems
12. Build

The detailed roadmap can be found in:

```
guide/roadmap.md
```

---

# Repository Structure

![Repository Structure](repo_structure.png)

Project folders are organized for learning, building, experimenting, and researching.

- `guide/` — Project documentation, roadmap, glossary, learning philosophy, and prerequisites.
- `notes/` — Personal learning notes and chapter summaries.
- `book/` — Polished educational content.
- `implementations/` — Code implementations built from scratch.
- `experiments/` — Experiments, comparisons, and observations.
- `research/` — Hypotheses, paper reviews, ideas, and future directions.
- `diagrams/` — Architecture diagrams, illustrations, animations, and mind maps.
- `resources/` — Books, papers, courses, datasets, and external references.
---

# Project Goals

By the end of this journey, you should be able to:

* Explain every major component inside an LLM.
* Understand why each component exists.
* Build a Transformer from scratch.
* Train a Tiny GPT.
* Implement an inference engine.
* Build a RAG system.
* Build an AI Agent.
* Design complete AI systems.
* Read modern research papers with confidence.
* Develop your own hypotheses and evaluate them critically.

---

# Prerequisites

This project assumes:

* Basic Python programming
* High-school algebra
* Curiosity
* Willingness to experiment

No prior AI or Machine Learning experience is required.

---

# Guiding Principle

Throughout this project, remember one simple idea:

> **Understanding is not the ability to repeat an explanation. Understanding is the ability to explain why a solution exists, rebuild it from scratch, recognize its limitations, and imagine how it could be improved.**

---

# Contributing

Contributions are welcome.

Whether you improve explanations, fix mistakes, add implementations, create diagrams, propose experiments, or review research papers, every contribution helps make this project a better learning resource.

Please read **CONTRIBUTING.md** before opening an issue or pull request.

---

# License

This project uses a dual-license model.

- **Code** (`implementations/`, `experiments/`, scripts, and software): **MIT License**
- **Educational Content** (`book/`, `guide/`, `notes/`, diagrams, and documentation): **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**

Please refer to the `LICENSE` file for complete licensing information.

---

# A Final Thought

Technology changes.

Frameworks change.

Models change.

APIs change.

But first principles remain.

This project is an attempt to learn AI in a way that remains valuable even as the field continues to evolve.

**Don't just learn Large Language Models—rediscover them.**
