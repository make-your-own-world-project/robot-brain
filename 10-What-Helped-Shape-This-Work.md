# What helped shape this work

![Public lessons return value while the people and works that contributed remain credited.](illustrations/publish-reciprocity-open-paths.png)

This page gives credit to the people, research, public projects, archives, and communities that shaped the work. The main explanation does not depend on knowing these names. They are here because influence should remain visible.

Commercial language models cannot name every person or work that shaped an answer. This project can be more specific about its own history.

## How the credit is recorded

An entry says who made the work, what it is called, where to find it, and how it affected the project. It also distinguishes direct use from testing, comparison, rejection, or general influence. When protected software or material was actually used, the applicable license is recorded too.

Those differences matter. Reading a paper is not the same as including its text. Testing a public program is not the same as adopting its design. Studying an approach can still influence later choices even when nothing from it is copied.

Like a musician naming the artists who influenced new music, this list explains what helped shape the work. It does not claim that every influence was incorporated. The separate [source, license, and privacy review](SOURCES-LICENSES-AND-PRIVACY.md) covers programs, trained files, and other material that was actually used or tested.

Credit does not mean endorsement, participation, or partnership. The people and organizations listed here remain responsible only for their own work.

## Detailed credit list

Some GitHub projects below performed limited analysis under their public terms. Others were studied, compared, or rejected. None of them served as training material for a new general language model.

## Literary, language, and communication foundations

| Person or group | Public source or named work | What it helped with | How it affected the project |
|---|---|---|---|
| Carlota S. Smith | *Modes of Discourse: The Local Structure of Texts* | Distinguishes kinds of writing and speech so they can be examined separately. | Design influence |
| M. A. K. Halliday and Ruqaiya Hasan | *Cohesion in English* | Shows that sentences can appear connected even when the overall meaning is unclear. | Design and measurement influence |
| M. A. K. Halliday | Register as field, tenor, and mode | Helps examine the subject, relationship, and form of a communication. | Design influence |
| Douglas Biber | *Variation across Speech and Writing* | Measures differences among kinds of speech and writing through groups of observable features. | Helped shape measurement of how explanations are organized |
| William Mann and Sandra Thompson | Rhetorical Structure Theory | Describes relationships between the main point of a passage and its supporting material. | Used in a working limited tool |
| John Swales | *Genre Analysis* | Describes the common steps used to organize different kinds of documents. | Document-planning influence |
| Gérard Genette and the Russian Formalist tradition | *Narrative Discourse*; fabula and sjuzhet | Separates event material from the order and viewpoint of its telling. | Narrative and history-building influence |
| H. P. Grice | “Logic and Conversation” | Helps distinguish intentional indirect meaning from an accidental communication failure. | Helped shape communication agreements and checks |
| Douglas Walton | Argumentation schemes and critical questions | Provides specific questions for examining an argument instead of hiding judgment in one score. | Helped shape how arguments are reviewed |
| Alexandra Aikhenvald | *Evidentiality* | Shows how language can indicate where information came from and what supports it. | Source-marking influence |
| Claude Shannon | “A Mathematical Theory of Communication” | Supplies formal ideas about information, limits of a communication channel, repetition, and loss. | Communication design influence |
| Herbert Clark and Susan Haviland | Given-new contract | Helps distinguish what a reader already knows from what a document must introduce. | Helped shape measurement of how explanations are organized |
| Morton Ann Gernsbacher | Structure-building framework | Helps examine how a reader forms and connects an understanding of a text. | Helped shape communication agreements |
| Benjamin Bloom; Lorin Anderson and David Krathwohl | Educational objective taxonomies | Supplies words for describing how deeply a reader should understand or use information. | Helped define what a document should help a reader do |

These works supplied methods and questions, not universal answers about a person. The design connects their limited methods while preserving where each one came from. Any conclusion drawn from them must remain open to checking and correction.

## Selecting, editing, and wording

| Person or group | Public source | What it helped with | How it affected the project |
|---|---|---|---|
| Jaime Carbonell and Jade Goldstein | “The Use of MMR, Diversity-Based Reranking for Reordering Documents and Producing Summaries” | Balances relevance against the need to add new information instead of repeating earlier material. | Adapted method |
| Hui Lin and Jeff Bilmes | Submodular summarization under budget | Helps select the most useful combination of material within a size limit. | Adapted method |
| Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka, and Aliaksei Severyn | LaserTagger | Demonstrates editing that can insert only words from an approved list. | Evaluated design influence |
| Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub, and Oleksandr Skurzhanskyi | GECToR | Demonstrates correction through a series of clearly labeled edits. | Evaluated design influence |
| Jonathan Mallinson, Jakub Adamek, Eric Malmi, and Aliaksei Severyn | EdiT5 | Demonstrates reordering existing material while limiting newly invented text. | Evaluated design influence |
| Eric Malmi and collaborators; the broader text-generation research community | Grammar-based, graph-to-text, and limited wording methods | Reinforces the separation of choosing content, planning, wording, and checking. | Design influence; the entire approach was not adopted as one package |

## Tools for reviewing documents, arguments, and supporting material

| Person or group | Public source | What it helped with | How it affected the project |
|---|---|---|---|
| Elena Chistova and IsaNLP contributors | [IsaNLP RST Parser program](https://github.com/tchewik/isanlp_rst), MIT; [v3 trained file](https://huggingface.co/tchewik/isanlp_rst_v3), CC BY-NC 4.0; and the cited ACL work | Suggests relationships between parts of a document. It does not determine personal meaning. | Used for one limited job under the trained file's noncommercial terms; no program or trained file is included here |
| Shon Otmazgin, Arie Cattan, Yoav Goldberg, and FastCoref contributors | [F-COREF paper and official project](https://github.com/shon-otmazgin/fastcoref), MIT | Suggests which words or phrases may refer to the same person or thing for later checking against the source. | Used for one limited job |
| Chris Reed, the ARG-tech group, AIF/xAIF contributors, and AMF/ARI contributors | [oAMF project list](https://github.com/arg-tech/oAMF), [AIF collections and tools](https://github.com/arg-tech/aif-arg-datasets), and linked descriptions | Describes limited relationships among claims and a shared way to record them. | AMF/ARI helped shape one limited tool; oAMF was studied but not adopted in full |
| Liyan Tang, Philippe Laban, and Greg Durrett | [MiniCheck](https://aclanthology.org/2024.emnlp-main.499/); [official project](https://github.com/Liyan06/MiniCheck) | Compares claims with the documents offered as support. | Tested; not allowed to approve a release |
| Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching, and Alex Deng | [FactCG](https://aclanthology.org/2025.naacl-long.258/); [official project](https://github.com/derenlei/FactCG) | Examines claims that depend on several connected pieces of evidence. | Tested; not allowed to approve a release |
| Philippe Laban, Tobias Schnabel, Paul N. Bennett, and Marti A. Hearst | [SummaC](https://aclanthology.org/2022.tacl-1.10/) | Shows why checking individual sentences can differ from checking a whole document. | Design influence |
| Lorena Scirè, Simone Conia, and Roberto Navigli | [FENICE](https://arxiv.org/abs/2403.02270) | Identifies claims and aligns them with evidence when evaluating summaries. | Design influence |
| Xiangkun Hu and collaborators | [RefChecker](https://github.com/amazon-science/RefChecker) | Records whether evidence supports, contradicts, or does not address a claim. | Evaluated design influence |
| Trieu H. Trinh and collaborators | [AlphaGeometry](https://github.com/google-deepmind/alphageometry) | Shows how a conclusion can retain an explicit path back through each supporting step. Its geometry rules are not used. | Design influence |

MiniCheck and FactCG were tested using recorded public versions and their stated licenses. Their scores did not reliably separate important changes in project-shaped test material, so their results were recorded as observations rather than release approval. The tools remain credited for what they can observe.

## Computer tools used by the project

The following public computer tools perform limited jobs. Their copyright notices and licenses control how they may be shared. These documents do not include copies of them.

| Tool | People or organization responsible | Recorded license | Job it performs |
|---|---|---|---|
| spaCy and its language models | Explosion language model, Matthew Honnibal, Ines Montani, and contributors | MIT | Identifying word roles, word forms, sentence relationships, and other language structure |
| BlingFire | Microsoft and contributors | MIT | Finding sentence boundaries |
| LemmInflect | Brad Jascob and contributors | MIT | Producing different grammatical forms of English words |
| submodlib | Vishal Kaushal, Rishabh Iyer, Ganesh Ramakrishnan, and DECILE contributors | MIT | Selecting a useful combination of material within a limit |
| NLTK | Steven Bird, Edward Loper, Ewan Klein, and contributors | Apache-2.0 | Access to language collections and language-analysis utilities |
| NumPy | NumPy contributors | Several notices apply to the current project and may vary with a built package; preserve the complete notice set for the exact version | Comparing large groups of measurements |
| SciPy | SciPy contributors | BSD-3-Clause | Comparing and grouping measurements |
| NetworkX | NetworkX contributors | BSD-3-Clause | Recording and examining connections |
| kneed | Kevin Arvai and contributors | BSD-3-Clause | Finding the point where further adjustment produces little improvement |
| PyYAML | Kirill Simonov and contributors | MIT | Reading and writing settings |
| httpx | Tom Christie and contributors | BSD-3-Clause | Letting connected services communicate |
| psycopg | Daniele Varrazzo and contributors | LGPL-3.0 | Access to saved records |
| Pydantic | Pydantic contributors | MIT | Checking that information has the expected form |
| OpenVINO | Intel and contributors | Apache-2.0 | Running selected local language-model tools when configured for that job |
| textdescriptives | Lasse Hansen, Kenneth Enevoldsen, and contributors | Apache-2.0 | Measuring readability, connection between ideas, and information density |
| LFTK | Bruce W. Lee and Jason Hyung-Jong Lee | CC BY-NC 4.0 in the repository's lowercase `license.txt` | Measuring language features during testing |
| vLLM | vLLM contributors | Apache-2.0 | Running the small local language model that adds a dated general-knowledge reading to completed conversations |
| Qwen3 | Alibaba Cloud and Qwen contributors | The official project states that its open-weight models use Apache-2.0 | Supplying the local language model used to connect findings from separate methods |

This table is a main list, not a complete legal notice for these tools. This document set names them but does not include their files. Any future release containing computer or language-model files must identify exactly what is included and carry every required notice, including requirements passed on by tools used inside other tools.

## Cultural works, language collections, archives, and communities

The main collection used to study how writing is organized consisted of works recorded as public domain. A small group of public standards expressly published for public use was examined separately. This was analysis, not the training of a new general language model.

The private source record identifies the works, their public source, why they were lawful to measure, and the part examined. The resulting study record does not keep copies of the writing. It keeps the observations, a short digital fingerprint used to confirm which material was examined, and directions back to the public source.

The confirmed sources were:

- public-domain books from Project Gutenberg, including children's stories, folk tales, short fiction, letters, diaries, household guides, and other historical writing;
- public-domain speeches and United States government works;
- historical newspaper pages from the Library of Congress collection that screens its material for known copyright restrictions;
- public-domain books connected to LibriVox records; no audio was downloaded or analyzed; and
- a small group of Internet standards whose own notices allowed unlimited distribution or free reproduction.

One large Project Gutenberg index released under CC BY 4.0 was inspected only to understand what it contained. Its book files were not downloaded or measured.

Project Gutenberg, its founder Michael S. Hart, Distributed Proofreaders, participating authors, editors, translators, and volunteers made much of this work possible. LibriVox volunteers and maintainers also deserve credit. So do the Library of Congress, the National Endowment for the Humanities newspaper program, the authors and publishers of the Internet standards, and the people who preserved the original works.

Other collections and communities appear in the wider research history. They include the Brown Corpus, Reuters-21578, NPS Chat Corpus, Universal Declaration of Human Rights translations, arXiv, PubMed/MEDLINE, Delpher, Wikipedia, Stack Overflow, Hacker News, and Mastodon. They supplied ideas, questions, possible comparisons, or separate research material. They are not the confirmed public-domain collection described above. None is being described as material used to train a new model. Their text, posts, and collection files are not included here.

The works and tools listed here keep their own rights and terms. This documentation records what each one made possible, where it fell short, and whether it was used, tested, or only studied.

Work returned by an outside language model is identified as model-generated work. Published research keeps its authorship. Sending selected material for one task does not turn the person's full saved history into a project asset or erase the rights of anyone represented in it.
