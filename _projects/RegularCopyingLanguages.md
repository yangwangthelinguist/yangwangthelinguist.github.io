---
layout: page
title: Regular copying languages
description: Reduplication as unbounded copying and its complexity
img: assets/img/rcls.png
importance: 1
category: work
---

Total reduplication is common in natural language phonology and morphology. However, productive total reduplication requires computational power beyond context-free, while other phonological and morphological patterns are regular, or even sub-regular. Thus, existing language classes characterizing reduplicated strings inevitably include typologically unattested context-free patterns, such as reversals. One line of my work extends regular languages to incorporate unbounded copying and examines the mathematical properties of the resulting language class.

---

For more details, see below:
- **Master's thesis**

    Wang, Yang. 2021. [Regular Languages Extended with Reduplication:  Formal Models, Proofs and Illustrations](https://escholarship.org/uc/item/4p03v92f).  Master's thesis, University of California, Los Angeles.
- **18th SIGMORPHON** (a short version of my master thesis)

    Wang, Yang. 2021. [Recognizing Reduplicated Forms: Finite-State Buffered Machines](https://aclanthology.org/2021.sigmorphon-1.20/). In Proceedings of the 18th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology, pages 177–187, Online. Association for Computational Linguistics.
- **2023 JLM paper** (an updated version of the proposed machine + a pumping lemma + discussions on *mode determinism* + some more theorems.)
    
    Wang, Yang and [Tim Hunter](https://timhunter.humspace.ucla.edu/). 2023. [On regular copying languages](https://jlm.ipipan.waw.pl/index.php/JLM/article/view/342). *Journal of Language Modelling*, 11(1), 1–66. https://doi.org/10.15398/jlm.v11i1.342

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/familiarlcs.png" title="familiar language classes" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rcls.png" title="regular copying languages" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, familiar language classes. On the right, The class of regular copying languages (oval shape) in the classical Chomsky Hierarchy. 
</div>


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/control.png" title="augmented copying" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Mode changes and input-buffer interaction of an FSBM M on ...abbabb...
</div>
