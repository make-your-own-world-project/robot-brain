# Follow one request through the working parts

![Separate parts preserve sources, record changes, gather findings, build results, and check them.](illustrations/public-machinery-catalog.png)

The clearest way to understand Robot Brain is to follow a saved conversation through it. No single part performs the whole job, and no language model controls the process.

## 1. LibreChat provides a screen

A changed version of LibreChat lets a person submit a request and read results in a familiar conversation.

LibreChat is not the memory or the intelligence of the project. Closing or replacing it does not remove the saved sources, findings, corrections, or approvals. Other screens can request the same underlying work.

## 2. The source keeper preserves the conversation

The person's messages, the language model's replies, and the order of the exchange are saved as the event that occurred.

Later summaries and interpretations are stored separately. They cannot replace the original messages or turn generated words into the person's own words.

## 3. Search finds possible material

Search narrows a large record to passages that may matter for a request. It does not decide that two events have the same meaning merely because they use similar words.

The passages remain connected to their original locations so a person or later check can inspect them.

## 4. Focused local readers examine specific features

Separate local methods look at language structure, statements, possible relationships, reasoning, time, human experience, and values.

Each method has a named subject and a limited authority. It reports findings tied to the passages it examined. It can say that no finding was supported. It cannot approve a final account or overwrite another result.

This is where much of the detailed analysis happens. It does not require a general-purpose language model to improvise the whole explanation in one pass.

## 5. The history record preserves change

Findings, corrections, disagreements, failed attempts, and unanswered questions are added in order. The current view can change without deleting the path that produced it.

This keeps a later fluent answer from hiding the work, uncertainty, and correction behind a conclusion.

## 6. Local Qwen supplies broad background when needed

The focused readers can produce accurate pieces that are difficult to understand together. A small Qwen model, served locally by vLLM, can read selected parts of a completed conversation and its findings.

Qwen's job is limited to adding a dated general-knowledge overview. It helps explain the ordinary background that the focused methods do not share.

Qwen is not trained on the person's history. It does not recover the original online model's hidden knowledge. The online model's actual contribution already survives in its saved replies. Another suitable model can replace Qwen without taking away those replies or the earlier analysis.

## 7. The request builder prepares the job

For an answer or document, the request builder identifies the purpose, reader, required questions, relevant evidence, and reasonable length. It records what material was included and omitted.

This step can prepare work for a fixed local process, a local model, an online model, or no model at all. It is not a forwarding service that sends every request to whichever language model is available.

## 8. A writer produces a candidate

A language model may draft or revise text when that is useful. Other work can be completed by search, fixed rules, or previously checked material.

The writer receives only the selected material and instructions for that job. Its response is a candidate, not a new fact and not an approval.

## 9. Independent checks and human approval decide what remains

Checks compare the candidate with its sources and requirements. They can catch missing evidence, unsupported claims, repeated material, or a result that does not match the request.

The approval record names the exact version accepted. The model that produced the candidate cannot approve itself.

## Why every part is replaceable

LibreChat is one screen. Qwen is one source of broad background. An online model is one optional worker. Search and focused readers are limited methods whose outputs can be rebuilt.

The lasting value is the preserved source, its history, the findings connected to it, and the record of what was accepted. Replacing one working part changes how a job is done; it does not erase the knowledge already preserved.

## Current scope

The parts described here exist in the current implementation or in recorded connected tests. Public claims distinguish current operation from separate tests, experiments, and future work. The project does not use the existence of one component as proof that every possible end-to-end use is complete.
