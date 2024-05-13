date:: 2022
title:: @You Actually Look Twice At it (YALTAi): Using an object detection approach instead of region segmentation within the Kraken engine
item-type:: [[journalArticle]]
access-date:: 2023-10-27T06:59:11Z
original-title:: You Actually Look Twice At it (YALTAi): Using an object detection approach instead of region segmentation within the Kraken engine
url:: https://arxiv.org/pdf/2207.11230.pdf
short-title:: You Actually Look Twice At it (YALTAi)
publication-title:: arXiv preprint arXiv:2207.11230
authors:: [[Thibault Clérice]]
links:: [Local library](zotero://select/groups/2386895/items/U3DEPCXR), [Web library](https://www.zotero.org/groups/2386895/items/U3DEPCXR)

- [[Abstract]]
	- Layout Analysis (the identification of zones and their classification) is the first step along line segmenta-
	  tion in Optical Character Recognition and similar tasks. The ability of identifying main body of text from
	  marginal text or running titles makes the difference between extracting the work full text of a digitized
	  book and noisy outputs. We show that most segmenters focus on pixel classification and that polygoniza-
	  tion of this output has not been used as a target for the latest competition on historical document (ICDAR
	  2017 and onwards), despite being the focus in the early 2010s. We propose to shift, for efficiency, the
	  task from a pixel classification-based polygonization to an object detection using isothetic rectangles. We
	  compare the output of Kraken and YOLOv5 in terms of segmentation and show that the later severely
	  outperforms the first on small datasets (1110 samples and below). We release two datasets for training
	  and evaluation on historical documents as well as a new package, YALTAi, which injects YOLOv5 in
	  the segmentation pipeline of Kraken 4.1.