---
layout: post
title: NFR Glossary
date: 2026-10-14 14:14:00
description: Non Functional Requirements and their meanings
tags: nfr glossary list
categories: nfr
---

## Intro

This post lists a fairly comprehensive list of Non Functional Requirements (NFRs), that I can relate back to in future blog posts. It's also useful as a stand alone piece, purely because it shows just how many different aspects of a system you may want to consider.

NFRs are system quality attributes, rather than specific processes or isolated numbers. Instead, an NFR is typically measured and validated through a collection of concrete metrics, the observation of which can, and should, be automated wherever possible.

## The List

**Security:** The protection of system assets, services, data, and communication channels against unauthorised access, malicious attacks, and data leakage.

**Performance:** The responsiveness and throughput of the system under a specified workload (e.g., latency, requests per second, CPU/memory utilisation).

**Scalability:** The ability of the system to handle increasing workloads by adding resources (horizontally or vertically) without degrading performance.

**Accuracy:** The precision, error tolerance, and acceptable margin of variance for calculations, probabilistic outputs (e.g., ML/AI), and data transformations.

**Cost Efficiency:** The ability to operate within defined infrastructure, licensing and LLM budgets, optimising resource spend per unit of work (e.g., cost per API call, compute efficiency).

**Accessibility:** The degree to which the software can be effectively navigated and used by people with diverse sensory, physical, and cognitive abilities.

**Usability:** The ease with which users can learn, navigate, and achieve goals within the interface, minimising cognitive load and operational error.

**Reliability:** The probability that the system will perform its intended function without failure over a defined period.

**Availability:** The proportion of time the system is fully operational and accessible to users when needed.

**Maintainability:** The ease with which developers can comprehend, debug, test, refactor, and safely deploy changes to the codebase.

**Flexibility:** The capacity to adapt to new business requirements, feature requests, or environment configurations with minimal code changes.

**Portability:** The ease with which the software can be migrated to and run across different operating systems, hardware architectures, container platforms, or cloud providers.

**Resilience:** The ability of the system to absorb failure, self-heal, gracefully degrade under stress, and recover quickly.

**Supportability:** The ease with which operations and support teams can diagnose incidents, resolve live issues, and maintain system health in production.

**Auditability & Traceability:** The ability to reconstruct historical actions, user interactions, data changes, and system decisions through immutable, tamper-evident logs for compliance.

**Reusability:** The degree to which system components, services, or modules can be reused in other applications or workflows without modification.

**Interoperability:** The ease with which the software exposes standard, well-documented interfaces (e.g., APIs, webhooks) to exchange data and integrate with external systems.

**Data Integrity & Quality:** The assurance that data remains consistent, valid, normalised, correctly structured, and free of unnecessary clutter across its entire lifecycle.

**Observability:** The ability to infer the internal health and behavior of the system based solely on its telemetry outputs (logs, metrics, and distributed traces).