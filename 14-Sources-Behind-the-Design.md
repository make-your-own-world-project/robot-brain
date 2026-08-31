# Research behind the design

![Different research traditions contribute limited methods while keeping their own histories.](illustrations/academic-framework-lineages.png)

This page is for readers who want the research trail. The main explanation does not require it.

The list includes ideas and tools that were used, tested, compared, rejected, or simply studied. Those relationships are not the same. Listing a source does not mean its authors participated in or endorsed the project.

## Keeping sources and changes over time

- Research on source history and changing information shaped the way records keep where material came from, when it applied, and what later replaced it.
- [Graphiti](https://github.com/getzep/graphiti) was examined as one approach to recording connections that change over time.
- Established change-recording methods informed the rule that a current summary must not replace the source behind it.

These ideas help preserve the path that a new model answer or rewritten summary would otherwise hide.

## Separating claims, support, and disagreement

- [Mann and Thompson's Rhetorical Structure Theory](https://aclanthology.org/J88-2003/) supplied names for relationships between parts of a document, such as a main point and its explanation.
- [Walton, Reed, and Macagno's Argumentation Schemes](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2) supplied focused questions for examining support and conclusions.
- [oAMF](https://github.com/arg-tech/oAMF) and xAIF supplied approaches for recording claims and their connections.
- [PropBank](https://aclanthology.org/J05-1004/) influenced how statements and the roles within them are recorded.
- [RSTformer](https://aclanthology.org/2023.acl-long.306/) and related work were tested for finding document structure. They were not used as final judges of meaning or reasoning.

These sources help prevent one polished paragraph from hiding the difference between a claim, its support, a correction, and a disagreement.

## Finding useful material without mistaking resemblance for truth

- [Carbonell and Goldstein's Maximal Marginal Relevance](https://aclanthology.org/X98-1025/) informed ways to balance relevance against repetition.
- [Lin and Bilmes on submodular document summarization](https://aclanthology.org/P11-1052/) informed ways to choose a useful group of passages within a size limit.
- [FActScore](https://aclanthology.org/2023.emnlp-main.741/) informed questions about how precisely claims are supported.
- Research on summaries built from recorded relationships informed tests that shorten material without throwing away the connections that matter.

Search and summarization can point a person toward evidence. They cannot decide why something mattered or make a passage true.

## Planning before writing

- [Reiter and Dale's Building Natural Language Generation Systems](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD) influenced the separation of choosing content, planning, and writing sentences.
- [Step-by-Step NLG](https://aclanthology.org/N19-1236/) and [data-to-text macro planning](https://aclanthology.org/D19-1318/) informed comparisons of document-planning methods.
- [SimpleNLG](https://github.com/simplenlg/simplenlg), [Grammatical Framework](https://www.grammaticalframework.org/), and [OpenCCG](https://github.com/OpenCCG/openccg) were evaluated as ways to turn planned content into sentences.
- Research on known and new information, connections between sentences, kinds of communication, and document forms influenced how explanations are ordered for different readers.

Together, this work supports planning a document before asking a language model to write it.

## Human understanding and reading cost

- Research on how people build understanding and manage mental effort informed limits on length, new concepts, and repetition.
- [Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270), [TAACO](https://www.linguisticanalysistools.org/taaco.html), [DocuScope](https://docuscope.github.io/), TextDescriptives, and LFTK were evaluated as ways to compare writing.
- Self-Determination Theory, research on meaning in life, and research on values informed limited questions about personal meaning. They do not support automatic diagnosis or broad profiles of people.

## Limited editing tools

[LaserTagger](https://github.com/google-research/lasertagger), [GECToR](https://github.com/grammarly/gector), and [EdiT5](https://aclanthology.org/2022.findings-acl.260/) were evaluated for editing tasks that limit how much new wording may be introduced.

## Rights and fuller records

This documentation does not include copies of the named books, papers, programs, trained model files, or research collections. [Sources, licenses, and privacy](SOURCES-LICENSES-AND-PRIVACY.md) records the license review for programs and trained files that were actually used or tested.

The private research record contains more papers, public standards, tools, collections, cultural works, rejected approaches, and test results. Public credit can grow as those records are checked, including ideas that helped mainly by showing what did not work.
