# Keep the record. Replace the model.

![A person's records remain in one place while separate working parts handle limited jobs.](illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain is software for preserving the history and meaning behind long-running human work. It is not a language model, a chatbot, or a service that forwards every question to a model.

Large language models can research, write, explain, and help solve difficult problems. The paid services built around them are still temporary workspaces. They can shorten a long conversation, lose earlier instructions, separate conclusions from their evidence, and continue writing as though the missing history were still present. A person then spends more time and paid usage rebuilding context that was already supplied.

This software changes where the lasting value lives. The person's conversations, documents, decisions, failed attempts, corrections, and unanswered questions remain in records the person controls. Local programs can examine those records. A language model can help with a selected job, but its contribution returns to the record as dated, reviewable work. The model can then be replaced without taking the history with it.

[Read this documentation in another language.](translations/README.md)

## The difference in one view

| A commercial language-model service | Robot Brain |
|---|---|
| Produces an answer from the material currently in its working view. | Keeps the complete source and the history around it. |
| May shorten or lose earlier conversation as work grows. | Saves conversations outside every model so they can be used again. |
| Blends knowledge learned from many sources without a complete path back to each source and its circumstances. | Keeps each known source, later finding, correction, and disagreement as a separate record. |
| Can write, search, plan, and judge its own answer in one exchange. | Gives saving, searching, analysis, writing, checking, and approval to separate parts with limited authority. |
| Controls the model, service rules, usage limits, and product changes. | Leaves the lasting record under the person's control. |
| Is paid for failed attempts and corrective exchanges as well as useful work. | Keeps failures and corrections so their lessons do not have to be purchased again. |

Robot Brain may call a local or online language model. That does not turn it into a model proxy. It can preserve, search, compare, organize, and rebuild earlier work without calling the model that took part in the original conversation. When a model is useful, the request is one step in a larger process that exists independently of that model.

## Why this was built

The strongest paid general-purpose models available during development were capable but unreliable custodians of long work.

Recorded failures included lost instructions, missing evidence, invented connections, premature claims of completion, unwanted changes, and damage to working files. Correcting those failures took more requests, more testing, more paid allowance, and more of the person's time and energy. The services did not automatically return the usage spent on unusable work or the exchanges needed to repair it.

The problem was larger than any one bad answer. A temporary text generator was being asked to serve as memory, historian, researcher, writer, checker, and final judge. Changing models did not change that arrangement.

Robot Brain was built around a different arrangement: keep the human record first, let several replaceable parts contribute to it, and require evidence outside the generating model before important work is accepted.

## What a trained model cannot keep

A large language model learns patterns from enormous collections of human work. Those patterns make the model useful, but the model is not a library of the complete works that shaped it.

Inside the model, influence from books, articles, conversations, translations, communities, labels, and human feedback is blended together. The model usually cannot show which sources shaped a particular sentence. It cannot restore every author's purpose, audience, evidence, disagreement, later correction, or missing viewpoint.

That is a loss of meaning even when the original work still exists elsewhere. The model retains some usefulness from the work while discarding the dependable path back to its human setting.

The same problem appears during ordinary use. A final answer may survive after the conversation that gave it meaning has been shortened. The conclusion remains, but the failed attempts, uncertainty, and reasons behind it disappear from the model's working view.

This project does not answer that problem by training another model on a person's life. Personal history remains readable and traceable instead of being blended into another trained model. Models work with selected records; they do not become the records.

## What each part does

The working software separates jobs that a chat service often makes look like one activity:

1. **The source keeper saves what happened.** It retains the conversation, document, image, or other material without replacing it with a summary.
2. **Searchable copies make the source easier to find.** Copied text, descriptions, and indexes point back to the unchanged source and can be rebuilt.
3. **Focused local readers examine specific features.** Separate methods look at language, statements, relationships, reasoning, time, human experience, and values. Each reports only its own findings and the passages behind them.
4. **The history record keeps change visible.** New findings, corrections, disagreements, failed attempts, and open questions are added without rewriting earlier events.
5. **The request builder gathers what one job needs.** It selects relevant sources and findings and records what was included or left out.
6. **A language model may add limited help.** A local model can supply broad background. An online model can assist with difficult research or writing. Either response remains a dated contribution that can be checked, rejected, or replaced.
7. **Separate checks compare the result with the request and evidence.** The model that wrote an answer cannot declare its own work accepted.
8. **A screen lets a person use the software.** The included LibreChat fork is one such screen. Replacing it does not replace the records or the other working parts.

No single part is presented as an all-knowing assistant. Their limited jobs are what make each part replaceable.

## Making a completed conversation useful again

A completed conversation contains the person's request, the language model's actual replies, the work attempted, the failures, the corrections, and the point where the exchange ended. Those messages preserve what the original model contributed without requiring that model to explain itself later.

Focused local readers examine the saved exchange from several angles. They can find detailed patterns and relationships without relying on broad world knowledge. Their separate findings remain connected to exact parts of the conversation.

Those findings may still need ordinary background knowledge before they form a clear account. For that limited step, a small Qwen model runs locally through vLLM. It adds a dated overview that helps connect the detailed findings and explain what the exchange accomplished.

Qwen does not recover the online model's hidden thoughts or training history. It supplies broad background knowledge that is not unique to the original model. The original model's useful contribution is already preserved in the words it produced.

The Qwen overview is stored beside the source and earlier findings. It can be corrected or replaced. The original conversation and detailed local analysis remain unchanged.

## What is working now

The current implementation can preserve a completed conversation, examine it through separate local methods, add a local general-knowledge reading, and gather every retained contribution into a record that can be rebuilt later.

It can also prepare a limited request for an online model when outside help is useful. That service receives only the selected material. Its answer returns to the local record, where checks and human approval—not the model—decide what is kept.

This is the central accomplishment: work that once depended on one temporary conversation can remain useful after its chat screen, model, and provider are gone.

## Read the full explanation

- [Why large language models cannot preserve the full story](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [What each part does—and what no model controls](02-A-Lasting-Record-Outside-the-Model.md)
- [Keep the correction without erasing the mistake](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Follow a claim back to the evidence](04-How-Every-Claim-Can-Be-Checked.md)
- [Build the document before writing the prose](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Explain the same truth to different readers](06-One-Meaning-Different-Readers.md)
- [Keep private history under the person's control](07-Privacy-and-Control-Stay-With-People.md)
- [What the current implementation does](08-What-Works-Today.md)
- [Why the design draws from many fields](09-How-Research-Strengthens-the-System.md)
- [Help without handing over private records](11-Contribute-Without-Giving-Up-Control.md)
- [Words used throughout these documents](12-A-Short-Guide-to-Key-Terms.md)
- [Follow one request through the working parts](13-The-Parts-Running-Today.md)
- [Use a language model for the job, not as the memory](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Failures observed in paid language-model services—and the safeguards they led to](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Lessons that changed the design](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Public-use, credit, and privacy notes](18-Use-Attribution-and-Limits.md)
- [How a completed conversation becomes lasting knowledge](19-What-the-System-Accomplishes.md)
- [What comes next](20-Where-the-System-Goes-Next.md)

## Credits, sources, and rights

- [What helped shape this work](10-What-Helped-Shape-This-Work.md)
- [Research behind the design](14-Sources-Behind-the-Design.md)
- [Sources, licenses, and public-release checks](SOURCES-LICENSES-AND-PRIVACY.md)

## License

The project's original writing, diagrams, and illustrations are available under the organization's [Creative Commons Attribution 4.0 International license](LICENSE.md), unless a document states different terms. Material created by others keeps its own rights and terms.

## Independence and privacy

This is an independent personal project developed on personal time, equipment, accounts, and paid services. No employer participated in it. Mentioning any person, employer, institution, model provider, research group, shared rule, or outside project does not imply participation, approval, partnership, or endorsement.

The public release excludes private records, identifying details, passwords, private connection information, employer information, and instructions for reaching private services. Descriptions of model failures are limited to recorded behavior and its effect; they do not claim undisclosed causes or motives. The documents are not professional advice or a promise of results.

![A path from provider-controlled memory toward records that remain with the people they concern.](illustrations/open-door-human-future.png)
