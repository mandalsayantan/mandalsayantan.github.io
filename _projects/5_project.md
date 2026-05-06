---
layout: page
title: Info|Phonology|Theory
description: A Dual-Level Information Framework for Phonological Computation.
img: assets/img/info_theory.png
importance: 5
category: work
related_publications:
---

**Quantifying the Abstract**

How do we measure "information" in a system like phonology, where the units (features and phonemes) don't have "meaning" in the traditional sense? While we can measure the statistical probability of a sound occurring (Shannon Information), that doesn't tell us anything about the complexity of the grammar itself—the "competence" of the speaker. 

This project proposes that phonology requires a dual-level architecture to bridge the gap between abstract structural rules and real-time processing data.

**The Architecture: MDL + Surprisal**

We argue that the brain manages two distinct types of information simultaneously:

1.  **Structural Information (Competence):** Measured via **Minimum Description Length (MDL)**. This captures the "elegance" or simplicity of the grammar. The brain favors the shortest "code" to describe a language's rules.
2.  **Statistical Information (Performance):** Measured via **Shannon Surprisal**. This captures how predictable a sound is during real-time speech processing.



**The Interface: Why It Matters**

The central claim is that these two levels are not independent: the structural model selected by the brain (the "simplest" grammar) defines the very units that the statistical processor then counts. 

Take **vowel nasalization** as an example:
*   Does the brain store "nasal vowels" as separate items in the dictionary? (Lexical Model)
*   Or does it store a "rule" that adds nasality to a normal vowel? (Rule-based Model)

Using MDL, we can predict which model a learner will choose. This choice then changes the "surprisal" values we see in neural data (like EEG). By linking these two measures, we can finally explain why some "rare" patterns are easy to process while some "frequent" patterns remain difficult—it’s not just about how often you hear it, but how your brain has structured the rule behind it.

**Key Predictions**
*   **Structural Effects:** Lower structural complexity reduces processing costs, even when frequency is low[cite: 1].
*   **Acquisition Bias:** Learners prefer simple structural hypotheses before they have enough data to calculate statistics[cite: 1].
*   **Typological Shifts:** When a rule has too many exceptions, the brain "flips" from a rule-based model to a lexical one once a specific MDL threshold is crossed[cite: 1].
