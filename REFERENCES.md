# References

## Purpose

This document identifies standards, technologies, research areas, and organizations that are relevant to the development of the ADE Human Machine Framework.

ADE does not claim ownership of these standards or technologies.

The purpose of this document is to:

1. Recognize existing work
2. Avoid unnecessary reinvention
3. Identify related architectures
4. Support research and comparison
5. Identify areas where ADE may complement existing standards
6. Help define where ADE is different from existing approaches

This document will evolve as ADE research continues.

---

# 1. Semantic Information and Linked Data

## RDF

**Organization:** World Wide Web Consortium (W3C)

Resource Description Framework (RDF) provides a model for representing information as relationships between resources.

RDF is relevant to ADE because ADE may need to represent information independently from the way that information is presented to a human or machine.

RDF provides an important foundation for representing meaning and relationships.

**Relevance to ADE**

ADE should build upon existing semantic information models rather than create another general purpose data model without need.

---

## JSON LD

**Organization:** World Wide Web Consortium (W3C)

JSON LD provides a JSON based representation for linked data.

It allows structured information to be represented in a form that can be used by existing web and software systems.

**Relevance to ADE**

JSON LD may provide one possible representation format for ADE information.

ADE is not intended to replace JSON LD.

---

## Schema.org

**Organization:** Schema.org

Schema.org provides a shared vocabulary for structured data used across the web.

It defines common types and properties for describing entities, events, organizations, places, products, actions, and other information.

**Relevance to ADE**

Schema.org demonstrates the value of shared semantic vocabularies.

ADE may build upon or reference existing vocabularies rather than duplicate concepts that already have broad adoption.

---

# 2. Web of Things and Machine Interoperability

## Web of Things

**Organization:** World Wide Web Consortium (W3C)

The W3C Web of Things work defines models and mechanisms for describing and interacting with connected things.

The Thing Description provides machine readable information about the capabilities and interactions of a thing.

**Relevance to ADE**

WoT is relevant to the relationship between information, devices, capabilities, and interaction.

ADE research must determine whether its proposed human first decision layer provides something that existing device and interaction architectures do not.

---

## OPC UA

**Organization:** OPC Foundation

OPC Unified Architecture is a platform independent framework for industrial interoperability and information exchange.

It provides mechanisms for representing information, relationships, states, capabilities, and interactions between industrial systems.

**Relevance to ADE**

OPC UA demonstrates that rich semantic information can exist independently from a particular user interface.

It is particularly relevant when considering ADE in industrial environments and human machine interaction.

---

# 3. Context Information

## NGSI LD

**Organization:** European Telecommunications Standards Institute (ETSI)

NGSI LD provides a standard model and API for managing context information.

It supports entities, properties, relationships, and contextual information.

**Relevance to ADE**

Context is an important part of the ADE hypothesis.

ADE research must examine how existing context information standards could provide the environmental and situational information needed to determine an appropriate human experience.

---

# 4. Accessibility and Alternative Experiences

## Web Content Accessibility Guidelines

**Organization:** World Wide Web Consortium (W3C)

WCAG provides recommendations for making web content more accessible to people with disabilities.

WCAG addresses areas including perceivability, operability, understandability, and robustness.

**Relevance to ADE**

WCAG is important to ADE because it demonstrates that information can be presented through different mechanisms while preserving access to its meaning.

ADE is not intended to replace accessibility standards.

ADE explores a broader question:

> Can information be architected independently from presentation from the beginning, rather than making an existing presentation accessible afterward?

Accessibility is therefore one important application area for ADE, but it is not the complete purpose of ADE.

---

## WAI ARIA

**Organization:** World Wide Web Consortium (W3C)

WAI ARIA provides semantics that allow user interface elements and behaviors to be communicated to assistive technologies.

**Relevance to ADE**

WAI ARIA demonstrates the importance of separating interface meaning from visual presentation.

It is relevant to ADE research into semantic information and alternative experiences.

---

## WAI Adapt

**Organization:** World Wide Web Consortium (W3C)

WAI Adapt explores mechanisms for adapting content and interfaces according to user needs and preferences.

**Relevance to ADE**

WAI Adapt is particularly important to ADE research because it addresses personalization and adaptation.

ADE must determine where its proposed architecture differs from or complements this work.

---

## Cognitive Accessibility

**Organization:** World Wide Web Consortium (W3C)

W3C Cognitive Accessibility work addresses barriers that can affect people with cognitive and learning disabilities.

**Relevance to ADE**

ADE considers information complexity, attention, comprehension, interaction requirements, and the ability to consume information according to human circumstances.

This makes cognitive accessibility an important research area.

---

# 5. Emergency Information

## Common Alerting Protocol

**Organization:** OASIS

The Common Alerting Protocol (CAP) provides a standard format for emergency and public warning information.

CAP allows an alert to contain structured information such as the event, urgency, severity, certainty, affected areas, and recommended actions.

**Relevance to ADE**

CAP is an important example of information being represented independently from a particular delivery mechanism.

It provides a useful comparison for ADE concepts such as:

* Event
* State
* Location
* Urgency
* Significance
* Applicability
* Action
* Timing

ADE research should determine whether its proposed architecture can build upon existing alert standards such as CAP.

---

# 6. Research Areas

The following research areas are relevant to ADE.

## Human Computer Interaction

Research into how humans interact with computing systems.

ADE is concerned with moving beyond screen first interaction toward interaction that considers the human, information, intent, context, and available capabilities.

---

## Context Aware Computing

Research into systems that use information about the environment, activity, location, and situation to change their behavior.

This is directly relevant to the ADE concept of context appropriate information experiences.

---

## Ubiquitous Computing

Research into computing that is integrated into everyday environments rather than limited to traditional computers.

This is relevant to ADE because information may increasingly be delivered through many devices and environments.

---

## Ambient Computing

Research into computing environments in which technology becomes integrated into the surrounding environment and interaction becomes less dependent on explicit device use.

This is relevant to the ADE goal of reducing unnecessary attention toward a particular device.

---

## Multimodal Interaction

Research into interaction using multiple human senses and communication channels.

Relevant modalities include:

* Visual
* Audio
* Haptic
* Thermal

ADE does not currently prescribe which modality should be used.

The receiving en
