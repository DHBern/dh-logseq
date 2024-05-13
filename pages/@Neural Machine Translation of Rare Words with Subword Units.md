tags:: [[Computer Science - Computation and Language]]
date:: [[Jun 10th, 2016]]
title:: @Neural Machine Translation of Rare Words with Subword Units
item-type:: [[journalArticle]]
access-date:: 2022-01-14T14:24:16Z
original-title:: Neural Machine Translation of Rare Words with Subword Units
url:: http://arxiv.org/abs/1508.07909
publication-title:: arXiv:1508.07909 [cs]
authors:: [[Rico Sennrich]], [[Barry Haddow]], [[Alexandra Birch]]
library-catalog:: arXiv.org
links:: [Local library](zotero://select/groups/2386895/items/SQ8DAIDN), [Web library](https://www.zotero.org/groups/2386895/items/SQ8DAIDN)

- [[Abstract]]
	- Neural machine translation (NMT) models typically operate with a fixed vocabulary, but translation is an open-vocabulary problem. Previous work addresses the translation of out-of-vocabulary words by backing off to a dictionary. In this paper, we introduce a simpler and more effective approach, making the NMT model capable of open-vocabulary translation by encoding rare and unknown words as sequences of subword units. This is based on the intuition that various word classes are translatable via smaller units than words, for instance names (via character copying or transliteration), compounds (via compositional translation), and cognates and loanwords (via phonological and morphological transformations). We discuss the suitability of different word segmentation techniques, including simple character n-gram models and a segmentation based on the byte pair encoding compression algorithm, and empirically show that subword models improve over a back-off dictionary baseline for the WMT 15 translation tasks English-German and English-Russian by 1.1 and 1.3 BLEU, respectively.
- [[Attachments]]
	- [arXiv.org Snapshot](https://arxiv.org/abs/1508.07909) {{zotero-imported-file 9JNLFU4B, "1508.html"}}
	- [arXiv Fulltext PDF](https://arxiv.org/pdf/1508.07909v5.pdf) {{zotero-imported-file 5XSE5MGD, "Sennrich et al. - 2016 - Neural Machine Translation of Rare Words with Subw.pdf"}}
- [[Notes]]
	- Comment: accepted at ACL 2016; new in this version: figure 3