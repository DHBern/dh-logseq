tags:: [[Computer Science - Computation and Language]], [[Computer Science - Cryptography and Security]], [[Computer Science - Machine Learning]]
date:: [[Dec 10th, 2021]]
extra:: arXiv: 2106.09898
title:: @Bad Characters: Imperceptible NLP Attacks
item-type:: [[journalArticle]]
access-date:: 2022-02-18T08:20:37Z
original-title:: Bad Characters: Imperceptible NLP Attacks
url:: http://arxiv.org/abs/2106.09898
short-title:: Bad Characters
publication-title:: arXiv:2106.09898 [cs]
authors:: [[Nicholas Boucher]], [[Ilia Shumailov]], [[Ross Anderson]], [[Nicolas Papernot]]
library-catalog:: arXiv.org
links:: [Local library](zotero://select/groups/2386895/items/CG9VBIHU), [Web library](https://www.zotero.org/groups/2386895/items/CG9VBIHU)

- [[Abstract]]
	- Several years of research have shown that machine-learning systems are vulnerable to adversarial examples, both in theory and in practice. Until now, such attacks have primarily targeted visual models, exploiting the gap between human and machine perception. Although text-based models have also been attacked with adversarial examples, such attacks struggled to preserve semantic meaning and indistinguishability. In this paper, we explore a large class of adversarial examples that can be used to attack text-based models in a black-box setting without making any human-perceptible visual modification to inputs. We use encoding-specific perturbations that are imperceptible to the human eye to manipulate the outputs of a wide range of Natural Language Processing (NLP) systems from neural machine-translation pipelines to web search engines. We find that with a single imperceptible encoding injection -- representing one invisible character, homoglyph, reordering, or deletion -- an attacker can significantly reduce the performance of vulnerable models, and with three injections most models can be functionally broken. Our attacks work against currently-deployed commercial systems, including those produced by Microsoft and Google, in addition to open source models published by Facebook, IBM, and HuggingFace. This novel series of attacks presents a significant threat to many language processing systems: an attacker can affect systems in a targeted manner without any assumptions about the underlying model. We conclude that text-based NLP systems require careful input sanitization, just like conventional applications, and that given such systems are now being deployed rapidly at scale, the urgent attention of architects and operators is required.
- [[Attachments]]
	- [arXiv.org Snapshot](https://arxiv.org/abs/2106.09898) {{zotero-imported-file 6SZ68YUE, "2106.html"}}
	- [arXiv Fulltext PDF](https://arxiv.org/pdf/2106.09898.pdf) {{zotero-imported-file ZW5UKUIB, "Boucher et al. - 2021 - Bad Characters Imperceptible NLP Attacks.pdf"}}
- [[Notes]]
	- Comment: To appear in the 43rd IEEE Symposium on Security and Privacy. Revisions: NER & sentiment analysis experiments, previous work comparison, defense evaluation