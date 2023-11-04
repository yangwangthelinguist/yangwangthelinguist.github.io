---
layout: page
title: Formal characterization of reduplication
description: A formal system that unifies reduplication with the rest of (morpho-)phonological processes
img: assets/img/rcls.png
importance: 1
category: work
---
In the classical Chomsky Hierarchy, productive total reduplication requires computational power beyond context-free, while other phonological and morphological patterns are regular, or even sub-regular. Existing language classes characterizing reduplicated strings are predicted to generate context-free patterns, such as the palindrome language. This does not match empirical observations. Reduplication, especially total reduplication, is well-attested, yielding various generalizations as the foundation for morphophonological theories. However, the palindrome pattern is not only rare in phonology and morphology, but also relies on conscious reasoning in its computation rather than on implicit linguistic knowledge.

One line of my work extends regular languages to incorporate unbounded copying. I developed a formal framework that unifies reduplication with other morpho-phonological processes by augmenting finite-state automata with queue-like memory storage. Mathematical properties of the resulting language class were further examined. This refinement to the classical Chomsky Hierarchy provides a better match to the language typology without sacrificing mathematical rigor.

---

For more details, see below:
- **Master's thesis**

    Wang, Yang. 2021. [Regular Languages Extended with Reduplication: Formal Models, Proofs and Illustrations](https://escholarship.org/uc/item/4p03v92f).  Master's thesis, University of California, Los Angeles.
- **18th SIGMORPHON** (a short version of my master's thesis)

    Wang, Yang. 2021. [Recognizing Reduplicated Forms: Finite-State Buffered Machines](https://aclanthology.org/2021.sigmorphon-1.20/). In Proceedings of the 18th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology, pages 177–187, Online. Association for Computational Linguistics.
- **2023 JLM paper** (an updated version of the proposed machine + a pumping lemma + discussions on *mode determinism* + some more theorems.)
    
    Wang, Yang and [Tim Hunter](https://timhunter.humspace.ucla.edu/). 2023. [On regular copying languages](https://jlm.ipipan.waw.pl/index.php/JLM/article/view/342). *Journal of Language Modelling*, 11(1), 1–66. https://doi.org/10.15398/jlm.v11i1.342

---
