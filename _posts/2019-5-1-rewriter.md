---
title:  "Faster constrained decoding and better sentence rewriting"
---

Constrained decoding, which we used in ParaBank, is not quite fast enough to be useful. We came up with an algorithmic improvement to boost its performance by 5-fold, and fixed a couple edge cases along the way. Armed with this improved framework, we showed that simply rewriting existing dataset and using it for data augmentation could give non-trivial improvement to an ELMo baseline.

The paper is titled "Improved Lexically Constrained Decoding for Translation and Monolingual Rewriting," which I presented at NAACL 2019 as a poster.

Check it out on ACL Anthology: [https://www.aclweb.org/anthology/N19-1090/](https://www.aclweb.org/anthology/N19-1090/) or [here](/assets/files/rewriter.pdf).
