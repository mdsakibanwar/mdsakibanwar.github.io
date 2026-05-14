---
title: "Logical Vulnerability Assessment: Detection, Analysis, and Reproduction"
collection: talks
type: "Invited Talk"
permalink: /talks/2026-epfl-hexhive
venue: "HexHive Group, École Polytechnique Fédérale de Lausanne (EPFL)"
date: 2026-04-13
location: "Lausanne, Switzerland (Virtual)"
---

As the software industry transitions toward memory-safe languages, a persistent misconception has emerged: that memory safety implies security. In reality, eliminating memory corruption exposes a deeper and largely unexplored class of flaws — logical vulnerabilities and resource exhaustion bugs — for which the existing analysis toolchain was not designed.

This talk examined why logical vulnerabilities matter, what makes them fundamentally harder to detect than their memory-corruption counterparts, and what a dedicated analysis infrastructure needs to look like to address them. The core challenge is that general-purpose analysis tools are built around assumptions that break systematically for runtime-managed languages: fixed memory layouts, no garbage collector, no interface dispatch at the IR level. Lifting to binary discards exactly the semantic information needed to reason about resource bounds and control flow in these languages.

The talk then addressed what it means to go beyond detection — arguing that for logical vulnerabilities, a finding without a structured, semantically grounded characterization is of limited operational value. Fuzzing, which has driven vulnerability discovery at scale for memory corruption, does not transfer cleanly to this class of bugs. The path forward requires analysis output that is rich enough to support proof-of-concept generation, root cause identification, and eventually patch synthesis — closing the loop from discovery to remediation.