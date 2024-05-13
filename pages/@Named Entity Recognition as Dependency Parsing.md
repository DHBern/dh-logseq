date:: 2020-07
publisher:: Association for Computational Linguistics
place:: Online
conference-name:: ACL 2020
proceedings-title:: Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics
doi:: 10.18653/v1/2020.acl-main.577
title:: @Named Entity Recognition as Dependency Parsing
pages:: 6470–6476
item-type:: [[conferencePaper]]
access-date:: 2023-06-27T11:36:27Z
original-title:: Named Entity Recognition as Dependency Parsing
url:: https://aclanthology.org/2020.acl-main.577
authors:: [[Juntao Yu]], [[Bernd Bohnet]], [[Massimo Poesio]]
library-catalog:: ACLWeb
links:: [Local library](zotero://select/groups/2386895/items/PGH2EN7V), [Web library](https://www.zotero.org/groups/2386895/items/PGH2EN7V)

- [[Abstract]]
	- Named Entity Recognition (NER) is a fundamental task in Natural Language Processing, concerned with identifying spans of text expressing references to entities. NER research is often focused on flat entities only (flat NER), ignoring the fact that entity references can be nested, as in [Bank of [China]] (Finkel and Manning, 2009). In this paper, we use ideas from graph-based dependency parsing to provide our model a global view on the input via a biaffine model (Dozat and Manning, 2017). The biaffine model scores pairs of start and end tokens in a sentence which we use to explore all spans, so that the model is able to predict named entities accurately. We show that the model works well for both nested and flat NER through evaluation on 8 corpora and achieving SoTA performance on all of them, with accuracy gains of up to 2.2 percentage points.