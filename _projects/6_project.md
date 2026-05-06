---
layout: page
title: Search | Alter
description: A parametric framework factorizing phonological computation into SEARCH and ALTER primitives.
img: assets/img/search_alter.png
importance: 6
category: work
related_publications:
---

**Deconstructing the Phonological Rule**

Traditional phonological rules often conflate "where to look" with "what to do." The **Search & Alter (S&A)** framework factorizes these into two independent computational primitives: a directional **SEARCH** procedure and a constrained **ALTER** operation. By treating these as distinct parameters, we can eliminate the need for complex "tiers" and instead derive locality as an emergent property of the search's termination conditions[cite: 1].

**The Core Architecture**

Every rule in S&A is defined by a specific set of parameters that dictate how the computation traverses a string of segments[cite: 1]:

*   **INR (Initiator):** The segment class that triggers the search[cite: 1].
*   **DIR (Direction):** The orientation of the search (left, right, or bidirectional)[cite: 1].
*   **MATCH (Relevance):** The predicate that defines which candidates are "seen" by the rule[cite: 1].
*   **TRM (Termination):** The predicate that defines accessibility—when the search must stop[cite: 1].
*   **ALTER (Operation):** The specific change, such as **COPYING** a feature from a target or **MODIFYING** a feature directly[cite: 1].

**Procedural Locality: Match vs. TRM**

The core theoretical insight of S&A is that what phonology "sees" (MATCH) and what it "can access" (TRM) are distinct[cite: 1]. Their interaction generates the diverse range of locality effects observed in human languages[cite: 1]:

| Configuration | Relation | Empirical Effect |
| :--- | :--- | :--- |
| **Closest Relevant** | MATCH = TRM | The search stops at the very first relevant candidate it encounters[cite: 1]. |
| **Blocking** | TRM ⊃ MATCH | An intervening segment (that isn't a match) forces the search to terminate, causing opacity[cite: 1]. |
| **Edge Selection** | MATCH ⊃ TRM | The search ignores intermediaries and only stops at a structural boundary (like a word edge)[cite: 1]. |

**Theoretical Implications**

By unifying previous models like *Search & Copy* and *Search & Change*, this framework accounts for vowel harmony, blocking, transparency, and non-assimilatory processes within a single, computationally controlled architecture[cite: 1]. It suggests that phonological competence is essentially a directional search combined with restricted feature alteration, providing a principled way to map the limits of phonological power[cite: 1].
