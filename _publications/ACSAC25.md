---
title: "VerDiff: Vulnerability Presence Verification for Comprehensive Reporting Using Constraint Programming"
collection: publications
permalink: /publication/ACSAC25
excerpt: 'VerDiff introduces a novel signature-matching framework to accurately identify all software versions affected by a vulnerability, correcting 265 misclassifications in official advisories.'
date: 2025-12-08
venue: 'Annual Computer Security Applications Conference (ACSAC) 2025'
keywords: {vulnerability management;constraint programming;software versioning}
githuburl: 'https://github.com/mdsakibanwar/verdiff'
dockerurl: 'https://hub.docker.com/r/sakibanwar/verdiff'
---
Effective cybersecurity relies on the public disclosure and tracking of program vulnerabilities, where an accurate list of affected program versions is critical for assessing security posture and orchestrating remediation. The precision of these lists is paramount, as a majority of industry systems operate with outdated dependencies and the average time to develop a patch is 256 days. As current solutions for determining affected versions do not scale to analyzing entire software release histories, we introduce **VerDiff**, a framework that employs a novel, payload-guided signature-matching technique for comprehensive vulnerability detection across all program versions. Beginning with an analyst's initial discovery, VerDiff formulates a multi-level signature that correlates dynamic binary analysis with source code features, enabling rapid triage while accounting for low-level nuances. In an evaluation of 27 CVEs across 11 distinct programs, VerDiff successfully identified 265 misclassifications within official security advisories, demonstrating its ability to significantly improve the accuracy of vulnerability reporting.