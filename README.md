# TOMATS Emotion Annotation (Soft Labels & Disagreement)

This repository accompanies the LREC-CAS 2026 paper:

> **TOMATS**: a case study of multilabel emotion annotation on Hemingway’s *The Old Man and the Sea*, treating annotator disagreement as signal rather than noise via soft-label aggregation and uncertainty-aware evaluation.

We provide code to reproduce the analyses and modeling experiments reported in the paper, including:
- missingness-aware inter-annotator agreement (IAA) analyses,
- soft-label construction (vote-share and intensity-weighted),
- disagreement metrics (e.g., distributional variance),
- co-occurrence and confusion diagnostics,
- baseline and transformer-based multilabel classification experiments,
- utilities to extract and summarize out-of-taxonomy “Other” emotion labels and notes.

> **Important note (copyright):** The underlying literary text is copyrighted. We therefore **do not redistribute the raw text** of *The Old Man and the Sea*. The code is written so that experiments can be reproduced using a locally obtained copy of the text and/or the derived, text-free annotation tables included here (keyed by item index). You can also contact the authors to obtain the exact splits used for this project.


---

How to cite

Please cite the paper if you use the code, derived annotations, or analyses:
```

@inproceedings{ohman2026quality,
  title     = {Quality and Agreement in Multilabel Emotion Annotation: A Case Study and Evaluation Framework},
  author    = {Emily Ohman and Anna Koufakou},
  booktitle = {Proceedings of the first Computational Affective Science workshop at LREC2026},
  year      = {2026},
  address   = {Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  url       = {PAPER_URL}
}

```
