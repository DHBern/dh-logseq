tags:: [[Computer Science - Computation and Language]], [[I.2.7]]
date:: [[Oct 5th, 2020]]
extra:: arXiv: 2004.03720
title:: @Byte Pair Encoding is Suboptimal for Language Model Pretraining
item-type:: [[journalArticle]]
access-date:: 2022-01-14T14:22:19Z
original-title:: Byte Pair Encoding is Suboptimal for Language Model Pretraining
url:: http://arxiv.org/abs/2004.03720
publication-title:: arXiv:2004.03720 [cs]
authors:: [[Kaj Bostrom]], [[Greg Durrett]]
library-catalog:: arXiv.org
links:: [Local library](zotero://select/groups/2386895/items/MDSSY4NF), [Web library](https://www.zotero.org/groups/2386895/items/MDSSY4NF)

- [[Abstract]]
	- The success of pretrained transformer language models (LMs) in natural language processing has led to a wide range of pretraining setups. In particular, these models employ a variety of subword tokenization methods, most notably byte-pair encoding (BPE) (Sennrich et al., 2016; Gage, 1994), the WordPiece method (Schuster and Nakajima, 2012), and unigram language modeling (Kudo, 2018), to segment text. However, to the best of our knowledge, the literature does not contain a direct evaluation of the impact of tokenization on language model pretraining. We analyze differences between BPE and unigram LM tokenization, finding that the latter method recovers subword units that align more closely with morphology and avoids problems stemming from BPE's greedy construction procedure. We then compare the fine-tuned task performance of identical transformer masked language models pretrained with these tokenizations. Across downstream tasks and two languages (English and Japanese), we find that the unigram LM tokenization method matches or outperforms BPE. We hope that developers of future pretrained LMs will consider adopting the unigram LM method over the more prevalent BPE.
- [[Attachments]]
	- [arXiv.org Snapshot](https://arxiv.org/abs/2004.03720) {{zotero-imported-file ZL8U5APT, "2004.html"}}
	- [arXiv Fulltext PDF](https://arxiv.org/pdf/2004.03720.pdf) {{zotero-imported-file TTK3RLK8, "Bostrom und Durrett - 2020 - Byte Pair Encoding is Suboptimal for Language Mode.pdf"}}
- [[Notes]]
	- Comment: 5 pages, 3 figures. To be published in Findings of EMNLP 2020