# ADE Human-Machine Framework: Architectural Hypothesis v0.1

## Status

Architectural Hypothesis

Version 0.1

Work in Progress

---

# Abstract

The ADE Human-Machine Framework (ADE-HMF) explores a human-first approach to information architecture.

Current digital ecosystems are largely designed around predetermined methods of consumption, most commonly screens. While accessibility technologies, personalization systems, and alternative interfaces improve access to information, they are often applied after information has already been structured around a primary presentation model.

ADE proposes an alternative architectural hypothesis:

**Information meaning should be separated from the experience used to consume it.**

Information should describe what exists, what is happening, what relationships exist, why it matters, and what action may be required without assuming a specific device, interface, language, or sensory channel.

The receiving environment determines the most appropriate experience based on the receiver, intent, context, and available capabilities.

This document introduces the hypothesis, outlines the proposed architecture, and identifies areas for future research and validation.

---

# 1. Problem Statement

Digital information is commonly architected for screens first and humans second.

As a result:

* People increasingly depend on screens to access information.
* Information consumption often competes with real-world attention.
* Accessibility solutions frequently adapt screen-based experiences rather than starting with human requirements.
* Information providers must create multiple experiences for different devices, languages, capabilities, and situations.
* Human, machine, and system interactions often require separate communication models.

The result is an ecosystem where information and experience are tightly coupled.

---

# 2. ADE Hypothesis

ADE proposes that information meaning and information experience should be treated as separate concerns.

Instead of designing information for a specific interface, information should describe:

* What exists
* What is happening
* Where it applies
* When it applies
* What relationships exist
* Why it matters
* What action may be required
* Who or what it applies to

The receiving environment then determines how the information should be experienced.

This allows the same information to be used by:

* Humans
* Machines
* Applications
* Vehicles
* Wearables
* Robots
* Future systems not yet invented

without requiring the original source to know the final receiver.

---

# 3. Core Principle

## Shared Meaning, Independent Experience

The source communicates meaning.

The receiver determines experience.

The same semantic information may be:

* Seen
* Heard
* Felt
* Summarized
* Expanded
* Translated
* Acted upon
* Deferred
* Ignored

depending on the receiver and context.

ADE does not attempt to define the interface.

ADE attempts to define the information required to support appropriate interpretation.

---

# 4. ADE Architectural Layers

The ADE Human-Machine Framework is organized into four conceptual layers.

## Layer 1: Semantic Information

This layer describes meaning.

Questions answered:

* What is it?
* What is happening?
* Where?
* When?
* How is it related?
* Why does it matter?
* What action may be required?
* Who or what does it apply to?

### Core Information Elements

| Element       | Purpose                                      |
| ------------- | -------------------------------------------- |
| WHAT          | Entity, object, event, action, state         |
| STATE         | Current condition                            |
| WHERE         | Location or scope                            |
| WHEN          | Time or duration                             |
| RELATIONSHIP  | Connections to other information             |
| SIGNIFICANCE  | Importance, urgency, consequence, confidence |
| REQUIREMENT   | Action or response requirements              |
| APPLICABILITY | Who or what is affected                      |

---

## Layer 2: Receiver Context

This layer describes the receiver and environment.

Questions answered:

* Who or what is receiving the information?
* What are they trying to accomplish?
* What is happening around them?
* What capabilities are available?

### Context Elements

| Element     | Purpose                                                  |
| ----------- | -------------------------------------------------------- |
| RECEIVER    | Human, machine, system                                   |
| INTENT      | Purpose or objective                                     |
| ACTIVITY    | Current activity                                         |
| ENVIRONMENT | Surrounding conditions                                   |
| LOCATION    | Current position or scope                                |
| CAPABILITY  | Available sensory, interface, or functional capabilities |

---

## Layer 3: ADE Decision Layer

This layer combines semantic information and receiver context.

Questions answered:

* What level of attention is appropriate?
* How much information is required?
* Is interaction necessary?
* When should the information be delivered?
* What action should be supported?

### Decision Elements

| Element           | Purpose                         |
| ----------------- | ------------------------------- |
| ATTENTION         | Required level of attention     |
| INFORMATION LEVEL | Summary, detailed, essential    |
| TIMING            | Immediate, deferred, contextual |
| INTERACTION       | Required, optional, unavailable |
| ACTION SUPPORT    | Guidance for potential action   |

### Example Outputs

#### Museum Exhibit

Attention: Available

Information Level: Summary

Interaction: Explore

#### Banking Transaction

Attention: Notice

Information Level: Essential

Interaction: Authorize

#### Wildfire Alert

Attention: Immediate

Information Level: Essential

Interaction: Acknowledge

Action Support: Evacuate

#### Driver Message

Attention: Available

Information Level: Summary

Timing: When Safe

Action Support: Call Back

---

## Layer 4: Experience Layer

This layer belongs to the receiving ecosystem.

ADE does not define presentation.

ADE does not define interface behavior.

ADE does not define device implementation.

The receiving system determines how to satisfy the requirements produced by the ADE Decision Layer.

Possible experiences include:

* Visual
* Audio
* Haptic
* Machine action
* Translation
* Summarization
* Expanded detail
* Interactive conversation

Different receivers may satisfy the same requirements in different ways.

---

# 5. Example Architecture

```text
                INFORMATION
                       │
                       ▼
             SEMANTIC INFORMATION
                       │
                       ▼
              RECEIVER CONTEXT
                       │
                       ▼
               ADE DECISION
                       │
                       ▼
                 EXPERIENCE
                       │
                       ▼
              HUMAN OR MACHINE
```

Expanded view:

```text
┌───────────────────────────────┐
│      SEMANTIC INFORMATION     │
│                               │
│ WHAT                          │
│ STATE                         │
│ WHERE                         │
│ WHEN                          │
│ RELATIONSHIP                  │
│ SIGNIFICANCE                  │
│ REQUIREMENT                   │
│ APPLICABILITY                 │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│       RECEIVER CONTEXT        │
│                               │
│ RECEIVER                      │
│ INTENT                        │
│ ACTIVITY                      │
│ ENVIRONMENT                   │
│ LOCATION                      │
│ CAPABILITY                    │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│        ADE DECISION           │
│                               │
│ ATTENTION                     │
│ INFORMATION LEVEL             │
│ TIMING                        │
│ INTERACTION                   │
│ ACTION SUPPORT                │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│         EXPERIENCE            │
│                               │
│ SCREEN                        │
│ AUDIO                         │
│ HAPTIC                        │
│ MACHINE ACTION                │
│ TRANSLATION                   │
│ SUMMARY                       │
│ DETAIL                        │
└───────────────────────────────┘
```

---

# 6. Human-Machine Scope

ADE is intended to support:

### Human to Human

Daughter communicates with father while driving.

### Human to Machine

Driver interacts with a vehicle navigation system.

### Machine to Human

Weather system informs a person of approaching conditions.

### Machine to Machine

Weather station informs an irrigation controller.

### Machine to Machine to Human

Wildfire sensor informs an emergency system which informs affected people.

### Human to Machine to Human

A person requests information from a system which delivers it appropriately to another person.

---

# 7. Relationship to Existing Technologies

ADE-HMF does not seek to replace existing standards and technologies.

Current standards already provide substantial capabilities for data representation, semantic relationships, device interoperability, accessibility, and machine communication.

Examples include:

* RDF (Resource Description Framework)
* JSON-LD
* Schema.org
* W3C Web of Things (WoT)
* WAI-ARIA
* WCAG
* WAI-Adapt
* Common Alerting Protocol (CAP)
* NGSI-LD
* OPC-UA

ADE-HMF explores whether an additional architectural layer exists between semantic information and experience determination.

Specifically, ADE investigates whether:

```text
Information Meaning
          +
Receiver
          +
Intent
          +
Context
          ↓
Experience Requirements
```

can be standardized independently of the final interface implementation.

---

# 8. Initial Research Questions

The ADE Human-Machine Framework remains a hypothesis.

Key questions include:

1. What is the minimum semantic information required to support appropriate interpretation?

2. Can a common decision model support both humans and machines?

3. Which ADE concepts already exist within current standards?

4. Which ADE concepts represent genuine architectural gaps?

5. Can information meaning remain stable while experiences vary across devices and contexts?

6. Can a common semantic model improve communication across human and machine ecosystems?

7. Can information providers remain independent of future devices and interaction models?

---

# 9. Working Principle

The central hypothesis of ADE-HMF is:

> Information describes what matters. Context determines how it should be experienced.

A supporting principle is:

> Shared Meaning, Independent Experience.

---

# 10. Related Standards and Technologies

The ADE Human-Machine Framework was developed after examining concepts from multiple technology domains, including:

### Semantic Technologies

* RDF
* JSON-LD
* Schema.org
* Knowledge Graphs
* Linked Data

### Accessibility and Personalization

* WCAG
* WAI-ARIA
* WAI-Adapt
* Inclusive Design

### Human-Computer Interaction

* Human Factors Engineering
* Context-Aware Computing
* Ubiquitous Computing
* Ambient Computing
* Multimodal Interaction

### Machine and Device Interoperability

* W3C Web of Things
* OPC-UA
* Event-Driven Architectures
* Context Information Management

ADE-HMF seeks to learn from and build upon these areas rather than replace them.

---

# 11. Future Research

Future versions of ADE-HMF should include:

* Comparative standards analysis
* Human factors research references
* Cognitive load and attention studies
* Accessibility research
* Context-aware computing research
* Multimodal interaction research
* Emergency communication models
* Human-machine communication studies

Additional work should focus on validating or disproving the ADE hypothesis through practical examples and implementation experiments.

---

# Architectural Origin

ADE Human-Machine Framework (ADE-HMF) is part of the broader ADE standards initiative originated by Arshad Darius Ebrahim.

The framework explores methods for enabling shared meaning across humans, machines, devices, and systems while allowing independent interpretation and experience based on context, intent, and capability.

Current status: Architectural Hypothesis v0.1.
...

## AI Assistance

Artificial intelligence tools were used during the development of this
document to assist with research, exploration, organization, questioning,
and drafting.

The architectural concepts, direction, decisions, and final content are
the responsibility of the originating Architect.

AI assistance does not represent authorship, endorsement, or validation
of the ADE architecture.
