tags:: [[000 Informatik]], [[Wissen & Systeme]], [[410 Linguistik]], [[Handwritten Text Recognition OCR Digital Humanities Ground Truth]], [[Institut für Computerlinguistik]], [[Linguistik Zentrum Zürich]]
date:: 2022
extra:: Publisher: European Language Resources Association
doi:: 10.5167/uzh-219356
title:: @Evaluation of HTR models without Ground Truth Material
item-type:: [[journalArticle]]
access-date:: 2023-02-21T15:38:25Z
rights:: info:eu-repo/semantics/openAccess
original-title:: Evaluation of HTR models without Ground Truth Material
language:: eng
url:: https://www.zora.uzh.ch/id/eprint/219356/1/2022.lrec_1.467.pdf
publication-title:: "LREC 2022, Marseille, 21 Juni 2022 - 23 Juni 2022, European Language Resources Association."
authors:: [[Phillip Ströbel]], [[Simon Clematide]], [[Martin Volk]], [[Raphael Schwitter]], [[Tobias Hodel]], [[David Schoch]]
links:: [Local library](zotero://select/groups/2386895/items/8CNMQWVW), [Web library](https://www.zotero.org/groups/2386895/items/8CNMQWVW)

- [[Abstract]]
	- The evaluation of Handwritten Text Recognition (HTR) models during their development is straightforward: because HTR is a supervised problem, the usual data split into training, validation, and test data sets allows the evaluation of models in terms of accuracy or error rates. However, the evaluation process becomes tricky as soon as we switch from development to application. A compilation of a new (and forcibly smaller) ground truth (GT) from a sample of the data that we want to apply the model on and the subsequent evaluation of models thereon only provides hints about the quality of the recognised text, as do confidence scores (if available) the models return. Moreover, if we have several models at hand, we face a model selection problem since we want to obtain the best possible result during the application phase. This calls for GT-free metrics to select the best model, which is why we (re-)introduce and compare different metrics, from simple, lexicon-based to more elaborate ones using standard language models and masked language models (MLM). We show that MLM-based evaluation can compete with lexicon-based methods, with the advantage that large and multilingual transformers are readily available, thus making compiling lexical resources for other metrics superfluous.
- [[Attachments]]
	- [UZH - Institut für Computerlinguistik - Phillip Ströbel, M.A.](https://www.cl.uzh.ch/de/people/team/compling/pstroebel.html) {{zotero-imported-file TAHY6YYQ, "pstroebel.html"}}