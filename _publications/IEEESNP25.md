---
title: "GoSonar: Detecting Logical Vulnerabilities in Memory Safe Language Using Inductive Constraint Reasoning"
collection: publications
permalink: /publication/IEEESNP25
excerpt: 'Inductive constraint reasoning is proposed to evaluate nontermination in Go programs, revealing five new vulnerabilities in the Go standard library.'
date: 2025-05-12
venue: '46th IEEE Symposium on Security and Privacy'
# slidesurl: 'http://mdsakibanwar.github.io/files/CheatFighter_Presentation.pdf'
paperurl: 'http://mdsakibanwar.github.io/files/GoSonar.pdf'
citation: "M. S. Anwar, C. Yagemann and Z. Lin, \"GoSonar: Detecting Logical Vulnerabilities in Memory Safe Language Using Inductive Constraint Reasoning,\" in 2025 IEEE Symposium on Security and Privacy (SP), San Francisco, CA, USA, 2025, pp. 43-43, doi: 10.1109/SP61157.2025.00043."
keywords: {symbolic execution;memory safety;nontermination}
---
As the global community advocates for the adoption of memory-safe programming languages, a significant research gap persists in identifying the critical vulnerabilities that follow. Logical vulnerabilities represent the most formidable threat to these programs, in the absence of memory safety related vulnerabilities such as buffer overflow. Go, a prevalent memorysafe language for cloud-based applications where resource availability is paramount, is especially susceptible to nonterminating, resource-exhaustive vulnerabilities. We present a novel approach to the problem, inductive constraint reasoning, designed to evaluate nontermination in complex, real-world programs, demonstrating superior performance compared to contemporary tools on a standardized dataset. Our methodology employs binary-level underconstrained symbolic execution to gather the constraints necessary for multiple recursive iterations. By applying a first-order derivative to these constraints, we model and classify various recursive functions, determining whether their subgoals converge to a global objective. This study addresses numerous challenges in the analysis of Go programs while simultaneously developing and implementing a practical solution to detect uncontrolled recursion, which has revealed 5 new vulnerabilities in the Go standard library.